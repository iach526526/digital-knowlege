---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 人工智慧與數位時代下的媒體與資訊素養
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
---

# 人工智慧與數位時代下的媒體與資訊素養


應數 1B 陳奕其

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/iach526526/digital-knowlege" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

## 關於本文
- 2025 出版的書選出來的文章
- 討論一篇 2018 探討人工智慧論文的想法
---

## 現在的世界

<v-clicks depth="2" every="1">



- 一種新的經濟模式
<!-- 注意力經濟 -->
- 兩種關鍵原料
<!-- 晶片和電，隨便湊好聽就好，還沒想到  -->
- 三大數位治理區塊
<!-- 歐盟,美國,中國  -->
- 四個雲端軍火商
<!-- Amazon, Google, Microsoft, Meta, Apple,甲骨文，依照我的喜好刪減 -->
<!-- 缺 五六七，還沒想到 -->
- 八十億人爭資源
</v-clicks>

---
layout: default
class: quote-page
title: 注意力經濟
---

<div class="quote-layout">
  <div class="quote-copy">
    <p class="eyebrow">諾貝爾經濟學獎得主</p>
    <h2>Herbert Simon</h2>
    <blockquote>
      資訊爆炸, 資訊當然不是稀有財; 資訊所消耗的東西 -- 也就是人的注意力 -- 變成了稀有財
    </blockquote>
  </div>

  <div class="quote-photo">
    <img src="/img/2026-06-07-10-19-21.png" alt="Herbert Simon" />
  </div>
</div>

<style scoped>


.quote-layout {
  height: 100%;
  min-height: 460px;
  display: grid;
  grid-template-columns: 1.35fr 0.9fr;
  gap: 2rem;
  align-items: center;
}

.quote-copy h2 {
  margin: 0.2rem 0 1rem;
  font-size: 2.4rem;
  line-height: 1.1;
}

.eyebrow {
  margin: 0;
  font-size: 0.95rem;
  letter-spacing: 0.08em;
  opacity: 0.7;
}

blockquote {
  margin: 0;
  padding-left: 1rem;
  border-left: 4px solid currentColor;
  font-size: 1.35rem;
  line-height: 1.75;
}

.note {
  margin-top: 1rem;
  font-size: 1rem;
  opacity: 0.75;
}

.quote-photo {
  display: flex;
  justify-content: center;
}

.quote-photo img {
  width: min(100%, 360px);
  max-height: 520px;
  object-fit: cover;
  border-radius: 24px;
  box-shadow: 0 18px 50px rgba(0, 0, 0, 0.18);
}

@media (max-width: 900px) {
  .quote-layout {
    grid-template-columns: 1fr;
    gap: 1.25rem;
  }

  .quote-copy h2 {
    font-size: 2rem;
  }

  blockquote {
    font-size: 1.15rem;
  }
}
</style>

<!-- 赫伯特·西蒙（司馬賀）曾經對當今經濟發展的趨勢進行過預測，他當時指出：「在如今這種資訊高速發展的時代中，注意力的價值將會超過資訊。」 -->
---

## 讀過用 AI 摘要嗎？

![why chinese class](/img/2026-06-06-18-14-02.png)

<!-- 讓 Google AI 摘要回答為什麼要上國文課。沒什麼特別的意思，就只是因為在國文報告想衝擊大家的思想體驗 -->
---
layout: image
image: /img/2026-06-06-13-50-37.png
backgroundSize: contain 
title: zero-click-chart
---

---

## stack overflow decline

![stack overflow decline](/img/2026-06-06-17-54-26.png)

---
title: 機器人造成網際網路上 HTTP 流量請求一半以上
image: /img/2026-06-09-11-43-07.png
layout: image-link
backgroundSize: contain
url: https://www.tomshardware.com/tech-industry/artificial-intelligence/bots-have-now-passed-human-traffic-online-cloudflare-boss-laments-says-agentic-traffic-wasnt-expected-to-eclipse-real-people-until-next-year
---

---


## AI 摘要讓我更快的拿到資料？這不好嗎？
- 每個人陷入語言模型建構的平行世界
- 作者想盡力傳達的「形式」消失了
- 簡化閱讀、去掉脈絡 => 思考退化
- 到底是誰在使用知識，我們還有「主體性」？
- 公共資源消失，世界的交流停留在 2023

<!-- 語言模型也是有個性的：討論 GPT, Gemini 對話的語氣和個性 -->



---
layout: fact
---

## 你認識的網際網路是什麼樣子？


---
layout: image
backgroundSize: contain
title: top websites from semrush.com
image: /img/2026-06-07-12-38-56.png
---

---
layout: image
backgroundSize: contain
title: 科技公司的花園高牆
image: /img/2026-06-09-12-05-45.png
---

---
layout: image-link
backgroundSize: contain
title: Talent São Paulo 廣告 | Go Outside iphone-prison
image: /img/2026-06-09-12-22-43.png
url: https://www.businessinsider.com/brazil-iphone-prison-2013-4
---


---
image: /img/my-browser-history.png
title: 我的瀏覽紀錄分析
layout: image
backgroundSize: contain
---

---

## 你了解你平常用的雲端服務嗎？

- 美麗的按鈕隱藏背後的邏輯
- 你享受免費服務，那公司到底怎麼賺錢？
- 

<!-- 講講微軟,line,Google,facebook。講難聽點就是你拉出來的屎進到馬桶後你以為會進化糞池，但其實是送到某個人家裡去供他研究 -->

---

## 三種策略
- 美式
  - 自由主義
- 中國
  - 整府立法擴全
    - 中共網絡安全法
- 歐盟
  - 立法限制科技公司行為，提供使用者最高的選擇權限
  - 推行自由軟體(Free software)
    - GDPR
---


## 語言模型有個性？

<div class="stack-gallery">
  <figure class="card left">
    <img src="/img/2026-06-06-17-24-51.png" alt="chatGPT-style" />
  </figure>
  <figure class="card center">
    <img src="/img/2026-06-06-17-25-08.png" alt="gemini-style" />
  </figure>
  <figure class="card right">
    <img src="/img/2026-06-06-17-25-23.png" alt="clude-style" />
  </figure>
</div>

<style scoped>
.stack-gallery {
  position: relative;
  height: 520px;
  margin-top: 0.5rem;
  perspective: 1400px;
}

.card {
  position: absolute;
  top: 50%;
  left: 50%;
  width: min(34vw, 400px);
  padding: 8px;
  box-shadow: 0 20px 44px rgba(0, 0, 0, 0.6);
  border-radius: 16px;
  margin: 0;
  transform-origin: center center;
}

.card img {
  display: block;
  width: 100%;
  height: auto;
}

.left {
  transform: translate(-122%, -50%) scale(1.02) rotate(-8deg);
  z-index: 1;
}

.center {
  transform: translate(-50%, -50%) scale(1.12) rotate(0deg);
  z-index: 3;
}

.right {
  transform: translate(22%, -50%) scale(1.02) rotate(7deg);
  z-index: 1;
}
</style>
---

## AI diplomacy

![AI diplomacy](/img/2026-06-06-17-14-01.png)

---

## 什麼是大語言模型？ 

- supervised learning(監督式學習)
- generativve adversarial networks gans(生成對抗式網路)
- reinforcement learning(強化式學習)

![generativve adversarial networks gans](/img/2026-06-06-18-00-29.png)

---

![The Meaning of Shoggoth AI Memes](/img/2026-06-06-17-50-35.png)

---

## AI 會講錯話？

- 大語言模型的模型檔不可能真的把所有資訊放進模型檔，他只會給出最常見、可能的回應
- 不要問 AI 個案
  - newyorker：[ChatGPT is a blurry jpeg of the web](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web?ref=hitripod.com)

---
title: ai-summery prompt injection
image: /img/2026-06-06-13-29-49.png
layout: image
backgroundSize: contain
---
---

## 認知上的平行世界
- 各持己見，無法溝通
- 無力感增加
- 逆來順受的事件應變

---

## 我們面臨著什麼樣的假資訊議題？


- 以假亂真的假資訊
  - Misinformation
    - 無心的錯誤訊息
  - disinformation
    - 錯誤+惡意訊息，例如 deepfake
  - Maliinformation
      - 根據事實，但斷章取意，惡意誤導的訊息

---
layout: fact
---

## 網路沒有國界

---
layout: image
image: /img/2026-06-06-18-07-50.png
backgroundSize: contain
title: Thread 網軍洗地
---

---
title: 公視新聞實驗室留言區
---

<div class="clickable-image-slide">
  <a href="https://www.youtube.com/watch?v=xgInd9VT1oU" target="_blank" rel="noreferrer">
    <img src="/img/pcomment.png" alt="p#新聞實驗室留言區" />
  </a>
</div>

<style scoped>
.clickable-image-slide {
  height: 100%;
  min-height: 420px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.clickable-image-slide a {
  display: block;
  width: 100%;
}

.clickable-image-slide img {
  display: block;
  width: 100%;
  max-height: 72vh;
  object-fit: contain;
}
</style>

---
layout: quote
---
凡伐國之道，攻心為上，攻城為下；心勝為上，兵勝為下

——孫臏 《長短經》

<!-- 不戰而屈人之兵，善之善者也 -->
---
layout: section
---

## 就是因為網路沒有管制才會這樣？

<v-clicks>

於是中介法出現了

</v-clicks>

---

## 長化短說數位中介服務法
- 管制內容提供商=> 那論壇網友的言論怎麼管？

---
image: /img/2026-06-07-22-16-12.png
backgroundSize: contain 
title: zero-click-chart
layout: image
---

<!-- 網友反對中介法 -->

---

## 讓中介法消失就是保護言論自由？
我們希望中介法做到的事

<v-clicks depth="2" every="2">



- 讓平台從「中立管道」變成「可被問責的資訊基礎設施」
  - 平台從資訊流動中獲利，也應承擔相應的社會責任
- 處理個人無法獨力承擔的網路風險
  - 假訊息、誹謗、隱私侵害，不能只靠使用者自律解決
- 打開大型平台的黑盒子
  - 演算法推薦、廣告投放、資料使用，都需要更高透明度
- 回應平台功能混合化的現實
  - LINE、社群平台、影音平台，已經不只是單純通訊或內容寄放
- 跟上國際平台治理趨勢
  - 歐盟《數位服務法》（DSA）已從「平台免責」走向「平台責任」
- 建立程序化、分級化的治理框架

</v-clicks>
<!--  -->
---

## 多方利害關係人模型

---

## 在這個時代，我們可以怎麼做？

- 拿回主控權
- 建立閱聽白名單
  - RSS！！
- 動腦思考（雖然堅信自己不會被影響的人往往是最容易被影響的）
- 用錢投票
  - 支持你覺得有幫助的軟體、媒體、軟體服務

---
layout: two-cols
---

## 

::right::
![g0v](/img/g0v-SITCON-2024.jpg)

---
layout: center
title: 沒有人
---

<div class="text-center text-4xl leading-tight">
  <VSwitch>
    <template #1>沒有人會願意做這些付出</template>
    <template #2>
      <div><s>沒有人會願意做這樣的付出</s></div>
      <h2><div>你就是沒有人！</div></h2>
    </template>
  </VSwitch>
</div>


---

## Ref
- [How Google AI Overviews is fuelling zero-click searches for top publishers](https://pressgazette.co.uk/media-audience-and-business-data/media_metrics/how-google-ai-overviews-is-fuelling-zero-click-searches-for-top-publishers/)
- [We Made Top AI Models Compete in a Game of Diplomacy. Here’s Who Won.](https://every.to/p/diplomacy)
- [Generative Adversarial Network (GAN)](https://www.geeksforgeeks.org/deep-learning/generative-adversarial-network-gan/)
- [SITCON 2026｜走進現場的價值：在 AI 時代，我們如何走向真相？|報導者營運長 李雪莉](https://www.youtube.com/watch?v=aoGGYKLk8G8)
- [奕站：服務條款太長了，就用 tosdr 看摘要吧！](https://www.iach.cc/tosdr/)
- [2025 年的台灣，一個網路平台，上頭有多少主管機關？ ](https://moztw.org/events/service-regulator/)
- [數位中介服務提供者的時代責任？專家學者觀點｜白廷奕](https://plainlaw.me/posts/expert-opinion-for-disa)
- [WiWik.Blog:我同意](https://www.wiwi.blog/blog/line-privacy-policy)
## 閱讀更多
[維基百科：注意力經濟](https://en.wikipedia.org/wiki/Attention_economy)

