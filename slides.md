---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /img/2026-06-09-21-31-21.png
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


應數 1B 陳奕其 蘇彥儒 陳亮羲
應數 1A 翁育宏

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/iach526526/digital-knowlege" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---
layout: image
image: /img/4.jpg
backgroundSize: contain
---
---
layout: image
image: /img/5.jpg
backgroundSize: contain
---
---
layout: image
image: /img/6.jpg
backgroundSize: contain
---
---
layout: image
image: /img/7.jpg
backgroundSize: contain
---
---
layout: image
image: /img/8.jpg
backgroundSize: contain
---
---
layout: image
image: /img/9.jpg
backgroundSize: contain
---
---
layout: image
image: /img/10.jpg
backgroundSize: contain
---
---
layout: image
image: /img/11.jpg
backgroundSize: contain
---
---
layout: image
image: /img/12.jpg
backgroundSize: contain
---
---
layout: image
image: /img/13.jpg
backgroundSize: contain
---
---
layout: image
image: /img/14.jpg
backgroundSize: contain
---
---
layout: image
image: /img/15.jpg
backgroundSize: contain
---
---
layout: image
image: /img/16.jpg
backgroundSize: contain
---
---
layout: image
image: /img/17.jpg
backgroundSize: contain
---
---
layout: image
image: /img/18.jpg
backgroundSize: contain
---
---
layout: image
image: /img/19.jpg
backgroundSize: contain
---
---
layout: image
image: /img/20.jpg
backgroundSize: contain
---
---
layout: fact
---

## TL;DR 課本原文
2025 出版的書討論一篇 2018 發布的人工智慧論文

<v-clicks>

~~學用落差就是這樣產生的，看看大家在學什麼東西~~

</v-clicks>
---
layout: two-cols-header
---

## 現在的世界

::left::

<v-clicks depth="2" every="1">


- 更多零日漏洞

- 一種新的經濟模式
  - 注意力經濟

- 兩個關鍵資源
  - 水＆電

- 三大數位治理區塊
  - 歐盟、美國、中國

- 四個虛擬戰場
  - 晶片、雲端基礎建設、模型、輿論

</v-clicks>

::right::

<v-clicks depth="2" every="1">

- 五種看不見的代價
  - 隱私、注意力、選擇的權利、公共討論、環境

- 六十億上網人口

- 七家公司左右未來
  - Microsoft、Nvidia、Apple、Alphabet、Amazon、Meta、Tesla 

- 八十億人爭資源
</v-clicks>
<style>
  .slidev-layout {
  font-family: "JetBrains Mono", "975HazyGo", ui-monospace, monospace, sans-serif;
  font-weight: 400;
  font-size: 1.3rem;
}
li>ul>li
{
  color:#6d6d6d;
}

</style>

<!-- 
1. zero day
2. 注意力經濟
3. 水和電
4. 歐盟,美國,中國
5. 晶片、雲端基礎建設、模型、輿論
6. 隱私、注意力、選擇的權利、公共討論、環境
7. 好像是 55 億的樣子 
8. Microsoft,Nvidia,Apple, Alphabet, Amazon ,Meta, Tesla 
9. 就...真的有這麼多人-->
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
layout: image-link
image: /img/2026-06-06-13-50-37.png
backgroundSize: contain
title: zero-click-chart
url: https://pressgazette.co.uk/media-audience-and-business-data/media_metrics/how-google-ai-overviews-is-fuelling-zero-click-searches-for-top-publishers/
---

<!-- 每日郵報的零點擊搜尋發生比率 -->
---

## stack overflow decline

![stack overflow decline](/img/2026-06-06-17-54-26.png)

<!-- 著名問答網站的活躍用戶雪崩下降 -->
---
title: 機器人造成網際網路上 HTTP 流量請求一半以上
image: /img/2026-06-09-11-43-07.png
layout: image-link
backgroundSize: contain
url: https://www.tomshardware.com/tech-industry/artificial-intelligence/bots-have-now-passed-human-traffic-online-cloudflare-boss-laments-says-agentic-traffic-wasnt-expected-to-eclipse-real-people-until-next-year
---

<!-- Cludflare 也表示網路上的人類 HTTP 流量已被 AI agent 超越。那這有什麼影響？ -->
---
layout: two-cols-header
---

## AI 摘要讓我更快的拿到資料，這不好嗎？

::left::
- 每個人陷入語言模型建構的平行世界
- 作者想盡力傳達的「形式」消失了
- 簡化閱讀、去掉脈絡 => 思考退化
- 到底是誰在使用知識，我們還有「主體性」？
- 公共資源消失，網路上的真實對話停留在 2023

::right::

![Big tech 灌食 AI](/img/2026-06-09-14-06-52.png)

<!-- AI 很方便，但其實有一部分的原因也是科技公司強推造成的。問：台下有沒有人知道除了 Google 以外的搜尋引擎，或是有誰不用 Google  -->
---
title: Google AI 搜尋強制上路，DuckDuckGo 安裝量一週衝高 30%：讓使用者自己決定要多少 AI
layout: image-right
image: /img/2026-06-09-14-10-22.png
backgroundSize: contain
---

## [把選擇權交給使用者](https://www.blocktempo.com/duckduckgo-installs-surge-thirty-percent-google-ai-search-force-fed-backlash/)

### 搜尋引擎
- DuckDuckGo
- kagi
- ~~Brave Search~~
<!-- 我沒那麼喜歡，因為他會強推自己的加密貨幣服務 -->
- Startpage
- Whoogle (selfhost)
- SearXNG (selfhost)

### 瀏覽器
- FireFox
- Vivaldi
- Heilum

<!-- 有的，還是有其他方案。瀏覽器和搜尋引擎是兩個不同的東西 -->
---
layout: center
---

## 你認識的網際網路是什麼樣子？

![open web](/img/2026-06-09-21-36-20.png)

---
layout: image
backgroundSize: contain
title: 科技公司的花園高牆
image: /img/2026-06-09-12-05-45.png
---

---
layout: image
backgroundSize: contain
title: top websites from semrush.com
image: /img/2026-06-07-12-38-56.png
---

---
layout: image-link
backgroundSize: contain
title: Talent São Paulo 廣告 | Go Outside iphone-prison
image: /img/2026-06-09-12-22-43.png
url: https://www.businessinsider.com/brazil-iphone-prison-2013-4
---

---
layout: image-link
image : /img/2026-06-10-10-12-03.png
backgroundSize: 30em 70%
---

## long tail theory

<style>

  body{
    background-ccolor:#FFFF;

}
</style>

<!-- Chris Anderson 提出，現在世界內容消費呈現長尾，短頭的現象。當然，也有蠻多人被關在高牆花園所以只有前三大網站 -->
---
image: /img/my-browser-history.png
title: 我的瀏覽紀錄分析
layout: image
backgroundSize: contain
---

<!-- 這是我的瀏覽器 2026 5 月的統計，大致符合長尾短頭的趨勢 -->
---
layout: two-cols
---

## 網路的組成
::right:: 
![網際網路堆疊](/img/2026-06-09-21-05-03.png)

<style>
  img{
width:89%  
  }

</style>

<!-- 讓我們來了解一下大家平常用的網路和雲端平台的現況 -->
---
transition: slide-up
layout: two-cols-header
---

## 你了解你平常用的雲端服務嗎？
::left::
- 按鈕背後的邏輯
- 你享受免費服務，那公司到底怎麼賺錢？
  - 對於所有的免費服務，你就是廠商最賺錢的工具

::right::
![click heatmap dashboard](/img/2026-06-09-21-14-10.png)


<!-- 講講微軟,line,Google,facebook 。講難聽點就是你拉出來的屎進到馬桶後你以為會進化糞池，但其實是送到某個人家裡去供他研究 -->
---
layout: two-cols
---

## Meta
- 管理人力不足，協同造假依舊盛行
- 高層不重視
- 為了擴展商業版圖，迎合特定元首政策
- 把當地罰金當成營運成本
::right::
<img src="/img/2026-06-09-14-51-50.png" class="max-w-full max-h-full object-contain" alt="社群帝國的那些人"/>

<style>
  img{
    width:60%;
  }
</style>

<!--
旗下產品還有 Thread, IG, Whatsapp
談劍橋分析、緬甸軍政府轉移
-->

---
layout: two-cols
---

## 劍橋分析
- 針對用戶投放特定貼文改變投票意願
- 2016 幫助川普成功當選總統

::right::

[![questioned Alexander Nix, chief executive of Cambridge Analytica](/img/2026-06-10-15-32-38.png)](https://www.nytimes.com/2018/03/17/us/politics/cambridge-analytica-trump-campaign.html)
<!-- 不是說反對廣告，但臉書本身的平台運作是有能力讓你完全看不到另一個候選人的聲音或作為，甚至是只會看到負面的事情，這和傳統看板廣告或新聞不一樣 -->

---
layout: two-cols-header
---

## 菲律賓介選
::left::
- 菲律賓總統當選人杜特帝用臉書操控民意
  - 將政治粉專冒充成可信的資訊來源
  - 監視人民
  - 鼓勵行刑隊

<v-click>

- Maria Ressa 得到諾貝爾和平獎
- Rodrigo Duterte 被國際刑事法院拘留（「違反人類罪」（毒品戰爭濫殺））
</v-click>


::right::
![A Thousand Cuts ](/img/2026-06-10-14-55-04.png)



<style>
  img{
    width:70%;
  }
.two-cols-header {
  column-gap: 3em;
}
</style>
<!-- 用臉書當作民意操控工具，在菲律賓也有一起，有關菲律賓總統 Rodrigo Duterte 。 現在其實已經不是那個資訊被發行需要被層層審視的時代了，過去我們有專業的編輯、記者、法律控管這些實體媒體，但在臉書上都不會有這些東西，很多人還是把臉書的某些粉專當成主要的新聞來源。-->
---
layout: two-cols-header
---

## 緬甸政變

::left::

- 在緬甸，Facebook 幾乎等同於網路入口
- 軍方、民族主義粉專、極端佛教僧侶利用 Facebook 散播反穆斯林、反羅興亞人的仇恨言論
- 2017 年軍方在若開邦發動「清剿行動」
  - 羅興亞人遭到屠殺、強暴、村莊焚毀
  - 超過 75 萬人逃往孟加拉

::right::

[![Hatebook](/img/2026-06-09-17-45-03.png)](https://www.reuters.com/investigates/special-report/myanmar-facebook-hate/)

<!--
在美國，Facebook 影響的是民主選舉；在菲律賓，Facebook 成為威權民粹的工具；但在緬甸，Facebook 的失靈直接連到族群清洗。
-->
---
layout: fact
transition: slide-up
---

## 無作為也是一種作為


---
layout: quote
transition: slide-up
---

## [一起來看看 LINE 條款](https://www.lycorp.co.jp/en/company/privacypolicy/)

We automatically collect information related to when and how you used our Services... For example, when using LINE, the contents that you posted, and texts, images, videos and sounds of the messages that you sent are sent via our server.

我們會自動收集有關您何時以及如何使用我們服務的資訊⋯⋯例如，當使用 LINE 時，您透過我們的伺服器發佈的內容、文字、圖片、影片和聲音訊息。

<v-click>

> 翻譯年糕：我們蒐集 Meta data

</v-click>

---
layout: quote
transition: slide-up
---

## [一起來看看 LINE 條款](https://www.lycorp.co.jp/en/company/privacypolicy/)

We may collect the location information of your device... Furthermore, in certain countries or regions (*2), when we provide customized contents or ads to you, such as local news near the areas where you are located, we may separately ask you to generally provide your location information and allow us to use such information.

Even when you do not accept sending your location information, we may estimate your approximate location by using information **such as your IP address**.

我們可能會收集您裝置的位置資料⋯⋯此外，在某些國家或地區(日本、台灣、泰國)，當我們向您提供客製化內容或廣告時，例如您所在區域附近的本地新聞，我們可能會單獨要求您一般性地提供您的位置資料並允許我們使用此類資料。

即使您不接受傳送您的位置資料，我們也可能會使用例如您的 IP 位址等資料來估計您的大致位置。
<v-click>

> 翻譯年糕：我們比你媽都還清楚知道你在哪，定位關了也可以透過你的 IP 反推位置
</v-click>
---
layout: quote
transition: slide-up
---

## [一起來看看 LINE 條款](https://www.lycorp.co.jp/en/company/privacypolicy/)

Unless you request the deletion of your account, in principle, we will retain most of your information. Once we receive your request to delete your account, we will delete your information according to Applicable Laws and internal rules after retaining such information for a given period of time.

除非您請求刪除您的帳戶，原則上，我們將保留您的大部分資料。一旦我們收到您刪除帳戶的請求，我們將在保留此類資料一段時間後，根據適用法律和內部規則刪除您的資料。
<v-click>

> 翻譯年糕：你用 LINE 傳送過所有東西存起來，直到永遠。照片會「過期」只是做給你看的，過期也不代表資料從伺服器上消失

</v-click>
---
layout: quote
---

## [一起來看看 LINE 條款](https://www.lycorp.co.jp/en/company/privacypolicy/)

We may use tags and modules containing cookies and third-party software development kit (SDK) for fulfilling the purposes described in this Policy. With regard to your Personal Data that is processed by a third-party through a module provided by such third party, the privacy policy of such third party will apply.

我們可能會使用包含 cookie 和第三方軟體開發工具包（SDK）的標籤和模組，以實現本政策中描述的目的。關於透過第三方提供的模組由第三方處理的您的個人資料，將適用該第三方的隱私政策。

<v-click>

> 翻譯年糕： LINE 會嵌入其他公司的程式碼，這些程式碼的功能可能會用來蒐集你的資料，會怎麼使用 LINE 不會負責

</v-click>
---
title: Terms of Service; Didn’t Read
image: /img/2026-06-09-14-36-13.png
layout: image-link
url: https://tosdr.org/en/about
---

---

## 什麼是大語言模型？ 

- supervised learning(監督式學習)
- generativve adversarial networks gans(生成對抗式網路)
- reinforcement learning(強化式學習)

<!-- ![generativve adversarial networks gans](/img/2026-06-06-18-00-29.png) -->

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
layout: image
image: /img/2026-06-09-18-14-35.png
backgroundSize: contain
title: 一切都基於電、水
---
---
layout: two-cols-header
---

## 《雲過無雨》
::left::

- 2020 台積電在美國亞利桑那州（這裡是沙漠）全資蓋晶圓廠
- 對周邊環境有什麼影響？
- 周圍居民怎麼想？


::right::

![](/img/2026-06-09-18-28-49.png)

<!-- 為了符合政策補貼、靠近其他供應商做出的選擇。水值得用工程解決的缺點（像是再生水）。再生水又要用一堆額外用電和化學處理 。

 AI 不只是大語言模型，它也會改變現實世界的資源分配。

-->
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
layout: section
---

## 台灣的課題

---
layout: two-cols-header
---

## 晶片很賺錢，也急需擴張規模...
::left::

<v-click  depth="2" every="1">

- 中國紫光集團大舉投資台灣半導體產業

<!--  -->
- 除了錢之外，還有什麼需要擔心的？
  - 技術外流
  - 人才流動
  - 供應鏈被重組


#2015 反紫光運動
</v-click>

::right::

![數位國土保戰](/img/2026-06-09-21-49-06.png)

<style>
  img{
width:70%  
  }

</style>
---
layout: image
image: /img/2026-06-06-18-07-50.png
backgroundSize: contain
title: Thread 網軍洗地
---

---
title: 公視新聞實驗室留言區

layout: two-cols-header
---

## [公視新聞實驗室留言區 AI 洗地干擾討論](https://www.youtube.com/watch?v=xgInd9VT1oU)
::left::

- 影片討論內容：領時薪比月薪高，打工當道？為何他們選擇非典型工作？
  - 這種留言區要怎麼正常討論？
::right::
![AI 洗地干擾](/img/pcomment.png)
---
title: 我是OO人：喊你「鄉親」的粉專，後台是內湖一間公司和一句忘了刪的 AI 指令
image: /img/2026-06-09-14-20-36.png
layout: image-link
url: 
---

<div class="absolute bottom-0 right-0 max-w-70">

[![我是OO人 粉專](/img/2026-06-09-14-21-57.png)](https://taiwan.md/society/%E6%88%91%E6%98%AFOO%E4%BA%BA/)

</div>
---
layout: quote
---
凡伐國之道，攻心為上，攻城為下；心勝為上，兵勝為下

——孫臏 《長短經》

<!-- 不戰而屈人之兵，善之善者也 -->
---
layout: fact
---

## 網路沒有國界。誰想讓我們減少討論？


---
layout: two-cols
---

![网络舆论引导](/img/2026-06-09-17-00-39.png)
::right::
![網路與輿論引導（台灣）](/img/2026-06-09-16-59-32.png)

<!-- 還是中共領先我們 20 年 -->

---
title: 換成「輿論 操控」這組關鍵字
layout: image
image: /img/2026-06-09-17-03-16.png
backgroundSize: contain
---
---
layout: two-cols-header
---
## 軟體開發生態受到挑戰
::left::
- AI 很快的挖出一堆漏洞
  - 最近一週一個 Linux 大漏洞
- AI agent 提出了很多看似有用的 Pull Request 讓人類維護者 review
  - 通常我們希望先處理真實人類的問題
::right::

![開源生態系](/img/CUP.png)

---

## 來不及講了，但你可以來研討會瞭解：）
[![COSUCP](/img/2026-06-09-18-07-52.png)](https://coscup.org/2026/)

---
layout: image
image: /img/2026-06-09-16-50-04.png
backgroundSize: contain 
title: Linux 漏洞連環爆
---

---
title: openClaw 代理 MJ Rathbun 寫 blog 怒罵人類拒絕他的程式變更請求
image : /img/2026-06-09-16-20-33.png
url: https://crabby-rathbun.github.io/mjrathbun-website/blog/posts/2026-02-11-gatekeeping-in-open-source-the-scott-shambaugh-story.html
layout: image-link
backgroundSize: contain
---
---
title: Anthropic警告AI可在數小時內打造漏洞攻擊程式
image : /img/2026-06-09-16-34-48.png
url: https://crabby-rathbun.github.io/mjrathbun-website/blog/posts/2026-02-11-gatekeeping-in-open-source-the-scott-shambaugh-story.html
layout: image-link
backgroundSize: contain
---

---
layout: image-link
image: /img/2026-06-09-16-32-17.png
---


---
layout: section
---

## 就是因為沒有管制才會這樣？

<v-clicks>

那...試著管管看吧...

</v-clicks>


---


## 三種策略
- 美式
  - 自由主義，容易放任監控式資本主義
- 中國
  - 政府立法擴權
    - 中共網絡安全法
- 歐盟
  - 立法限制科技公司行為，但實行成果仍需努力
  - 提供使用者最高的選擇權限
  - 推行自由軟體(Free software)
  - 訂立 GDPR

---

## GDPR 很棒，但...

- 某些公司出於惡意過度遵守規定，造成使用者不便
- 讓隱私責任轉嫁給使用者，並讓暗黑模式（dark mode） 成為常態
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

![Multistakeholder Model](/img/2026-06-10-16-11-59.png)
---

## 多方利害關係人模型

- 政府
  - 法律、公共責任、基本權利保障
- 平台與企業
  - 技術實作、資料透明、風險控管
- 公民社會
  - 監督、倡議、受害者經驗
- 技術社群
  - 開源工具、資安、標準與可驗證性
- 學界與媒體
  - 研究、查證、公共討論

> 讓不同領域的人一起來談，達成共識
---

## 在這樣的時局，有什麼我可以做的事？
<v-clicks>

- 大部分的人要清醒一點，主動要求拿回主控權
- 建立閱聽白名單
  - RSS！！
- 動腦思考（雖然堅信自己不會被影響的人往往是最容易被影響的）
- 多多表態，建立集體認知
- 用錢投票
  - 支持你覺得有幫助的軟體、媒體、軟體服務


</v-clicks>
<!-- 資料存在哪？有沒有放在中立國 -->
---
layout: two-cols
---

## g0v：用開源協作補民主的洞
- 台灣發起的公民科技社群
- 專注於公民科技的開發

::right::
![g0v](/img/g0v-SITCON-2024.jpg)

---

## 你可能聽過的專案

- 萌典
- 中央政府預算視覺化
- Cofacts 真的假的
- 公民攝影記者證產生器


---
layout: center
title: 沒有人
---

<div class="text-center text-4xl leading-tight">
  <VSwitch>
    <template #1>沒有人會願意付出這些</template>
    <template #2>
      <div><s>沒有人會願意做付出這些</s></div>
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
- [奕站：你有選擇自己的瀏覽器和搜尋引擎的權利](https://www.iach.cc/2026/browses/)
- [2025 年的台灣，一個網路平台，上頭有多少主管機關？ ](https://moztw.org/events/service-regulator/)
- [數位中介服務提供者的時代責任？專家學者觀點｜白廷奕](https://plainlaw.me/posts/expert-opinion-for-disa)
- [WiWik.Blog:我同意](https://www.wiwi.blog/blog/line-privacy-policy)
- [This company killed open source](https://www.youtube.com/watch?v=bpqFZBWcStU)
---

## 閱讀更多

- [維基百科：注意力經濟](https://en.wikipedia.org/wiki/Attention_economy)
- [報導者：假訊息、仇恨言論如何傷害民主 圍繞羅興亞人的資訊戰：當臉書變失控巨獸，緬甸政府反成最大贏家？](https://www.twreporter.org/a/asia-disinformation-fake-news-myanmar-government-facebook)
- [專訪前「劍橋分析」業務總監：只要臉書的生意繼續，民主就有危機](https://www.twreporter.org/a/information-warfare-business-interview-cambridge-analytica-brittany-kaiser)
- [Zei:Open Source Alternatives ](https://www.youtube.com/watch?v=tumUlLaC9cY)
- [SITCON 2026｜從網址之爭，帶你走進網路治理世界](https://www.youtube.com/watch?v=utOnFcoCbl0)
- [從網址之爭，帶你走進網路治理世界 - Arnoldsky](https://hackmd.io/@SITCON/2026/%2FrJRMJZic-x)
