---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /image-6.png
# some information about your slides (markdown enabled)
title: Die absurde Geschichte der Webentwicklung
info: |
  ## ITP Referat: Die absurde Geschichte der Webentwicklung

  Github Source Repository [Die Geschichte der Webentwicklung](https://github.com/jonasfroeller/Die_Geschichte_der_Webentwicklung).
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

<style lang="postcss">
  h1 {
    @apply bg-slate-900 rounded-lg px-2 py-2;
  }
</style>

# Die absurde Geschichte der Webentwicklung

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
     <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="flex gap-2 m-6 abs-br">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
# Die absurde Geschichte der Webentwicklung
-->

---
transition: slide-up
level: 2
---

# Inhalt

> Die absurde Geschichte der Webentwicklung

<br>

1. **Geschichtsstunde: Wie alles begann.**
   1. Browser
   2. Suchmaschinen
   3. Webtechnologien
2. **Was haben wir getan?**
3. **Die Zukunft**

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
# Inhalt

> Die absurde Geschichte der Webentwicklung

1. **Geschichtsstunde: Wie alles begann.**
   1. Browser
   2. Suchmaschinen
   3. Webtechnologien- und Standards: HTML5, CSS3, ES6
2. **Was haben wir getan? - Das Framework Massacre. (State of Frontend)**
3. **Die Zukunft** - Back to the roots? Haben wir einen vollen 360 gemacht?
-->

---
src: ./pages/history-lesson.md
hide: false
---

---
src: ./pages/framework-hell.md
hide: false
---

---
src: ./pages/future.md
hide: false
---

---
layout: default
---

# Danke!

> Ich habe eine Website innerhalb einer anderen Website programmiert, die diese Präsentation darstellt. <mdi-emoji-neutral />

<center>
  <PoweredBySlidev mt-10 />
</center>

<!-- <Toc minDepth="1" maxDepth="1"></Toc> -->

<!--
# Danke!
-->

---
layout: full
---

# Quellen

Fireship - "The Weird History of JavaScript": https://www.youtube.com/watch?v=Sh6lK57Cuk4  
Awesome - "A Brief History of the Web": https://www.youtube.com/watch?v=bSd8WJCzG-Y  
Flux Academy - "How did we get here? Web Design History From Dial-Up To The Weird Future.": https://www.youtube.com/watch?v=wlYjSThvtew

Browser Market Share: [gs.statcounter.com/browser-market-share#monthly-200901-202410](https://gs.statcounter.com/browser-market-share#monthly-200901-202410)  
Search Engine Market Share: [gs.statcounter.com/search-engine-market-share#monthly-200901-202410](https://gs.statcounter.com/search-engine-market-share#monthly-200901-202410)  
Framework Benchmarks: [krausest.github.io/js-framework-benchmark/2024/table_chrome_129.0.6668.58.html](https://krausest.github.io/js-framework-benchmark/2024/table_chrome_130.0.6723.58.html)  

[Weitere](https://github.com/jonasfroeller/Die_Geschichte_der_Webentwicklung/blob/main/Referat.md#quellen): Reddit, X (Twitter), Wikipedia, GitHub

![https://www.reddit.com/r/programminghumor/comments/1facshr/getting_roasted_by_vs_code_extensions/](/image-15.png)

<!--
# Quellen
-->
