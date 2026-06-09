<script setup lang="ts">
import { computed } from 'vue'
import type { CSSProperties } from 'vue'

const props = defineProps({
  image: {
    type: String,
  },
  backgroundSize: {
    type: String,
    default: 'cover',
  },
  url: {
    type: String,
    default: '',
  },
})

function resolveAssetUrl(url: string) {
  if (url.startsWith('/'))
    return import.meta.env.BASE_URL + url.slice(1)
  return url
}

function handleBackground(background?: string, dim = false, backgroundSize = 'cover'): CSSProperties {
  const isColor = background && (background[0] === '#' || background.startsWith('rgb'))
  const style: CSSProperties = {
    background: isColor ? background : undefined,
    color: (background && !isColor) ? 'white' : undefined,
    backgroundImage: isColor
      ? undefined
      : background
        ? dim
          ? `linear-gradient(#0005, #0008), url(${resolveAssetUrl(background)})`
          : `url("${resolveAssetUrl(background)}")`
        : undefined,
    backgroundRepeat: 'no-repeat',
    backgroundPosition: 'center',
    backgroundSize,
  }
  if (!style.background) delete style.background
  return style
}

const style = computed(() => handleBackground(props.image, false, props.backgroundSize))

function openLink() {
  if (props.url)
    window.open(props.url, '_blank')
}
</script>

<template>
  <div
    class="slidev-layout w-full h-full"
    :class="{ 'cursor-pointer': !!url }"
    :style="style"
    @click="openLink"
  >
    <slot />
  </div>
</template>
