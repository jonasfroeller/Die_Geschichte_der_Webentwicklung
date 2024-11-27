---
level: 4
layout: section
---

# Die Zukunft

<!--
# Die Zukunft
-->

---
level: 2
layout: image-right
image: /image-12.png
---

# Ständiger technologischer Wandel

> Updates kommen ohne "Zustimmung" und schneller als man "Webscraper" sagen kann.

````md magic-move {lines: true}
```html
<div id="sanity">
  <span data-sanity-lvl="42">42</span>
</div>
```

```html
<div class="sanity">
  <span class="sanity-lvl">69</span>
</div>
```
````

<!-- Image Source: https://www.reddit.com/r/programminghumor/comments/1gb9esr/scrapers/ -->

<!--
# Ständiger technologischer Wandel

> Updates kommen ohne "Zustimmung" und schneller als man "Webscraper" sagen kann.
-->

---

# Webentwicklung Heute

> Es hat sich einiges getan!

```ts {monaco-run}
import { version } from 'vue'
import { emptyArray } from './editor'

console.log(`vue ${version}`)
console.log(emptyArray<number>(10).reduce(fib => [...fib, fib.at(-1)! + fib.at(-2)!], [1, 1]))
```

* Serverless
* WebAssembly
* PWAs
* Toolchains

<!--
# Webentwicklung Heute

> Es hat sich einiges getan!

## Serverless

* Wartung und 
* Skalierung übernimmt ein PaaS

## WebAssembly

* seit 2015
* Kompilierung von effizienten Sprachen in Browser-lesbares Format

## PWAs

* Website kann von der Website aus installiert werden.
* Website funktioniert auch offline.

## Neue Toolchains (jetzt auch schnell)

* Bun (Zig)
* Deno (Rust)
* VoidZero (Rust)


Mehr Infos:
___

1. Serverless

Serverless Computing ist ein Cloud-Computing-Modell, das Entwicklern ermöglicht, Anwendungen zu erstellen und auszuführen, ohne sich um die zugrunde liegende Serverinfrastruktur kümmern zu müssen.

* Wartung und Skalierung übernimmt ein PaaS
* Function as a Service (FaaS): Lambda
* Backend as a Service (BaaS): Datenbankmanagement oder Authentifizierung

2. WebAssembly

WebAssembly (Wasm, 2015) ist ein offener Standard, der eine portable, binäre Codeformatierung für die Ausführung von Programmen in Webbrowsern definiert. Es ermöglicht Entwicklern, Code, der in Hochsprachen wie C, C++ oder Rust geschrieben ist, in ein kompaktes und effizientes Format zu kompilieren, das mit nahezu nativer Geschwindigkeit im Browser ausgeführt werden kann.

3. PWAs

* Website kann von der Website aus installiert werden.
* Website funktioniert auch offline.
* Service Worker: Mittelsmann zwischen Browser und Webapp
  * Offline-Nutzung, 
  * Push-Benachrichtigungen und 
  * Hintergrundsynchronisation
* Manifest

4. Toolchains (jetzt auch schnell)

* Bun (Zig)
* Deno (Rust)
* VoidZero (Rust)
-->
