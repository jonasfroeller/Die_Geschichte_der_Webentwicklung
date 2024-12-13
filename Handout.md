# Handout

## Geschichtsstunde: Wie alles begann.

### Entwicklung des Internets

- 1990: Tim Berners-Lee entwickelt den ersten Browser, Start mit einfachen HTML-Seiten.
- 1992: Erstes Bild wird hochgeladen.
- 1997: Websites wachsen von 10 auf über 1 Million.
- 1993-2021: Flash-Ära - Animationen und Spiele (RIP, [killed by Google](https://killedbygoogle.com), 296)
- 1997 (EOT), 1998 (@font-face): Web-Fonts in Internet Explorer (@font-face: 2009 in Safari und Firefox :skull:)
- 2007: "iPhone 1" => Mobile und responsive Designs

### Entwicklung der Webentwicklung

- 2005: Google macht AJAX (async js/xml) - "the xml http thing" groß
- 2007: jQuery wird bekannter und damit clientseitiges rendering mehr
- 2008: Chrome wird veröffentlicht und setzt neue Maßstäbe in Leistung und Nutzererfahrung
- 2010: Aufstieg der JavaScript-Frameworks und von NodeJS (SPAs, SSR, REST Microservices)
- 2016: AngularJS wird Angular (JS => TS), React & Vue etablieren sich
- 2022: Back to the roots: SSR erlebt eine Renaissance
- JETZT: Astro, ein SSR Framework mit Adaptern für Frontend-Frameworks, HTMX (HATEOAS (Hypermedia as the Engine of Application State)), Typescript ist Industriestandard

### Standards

- HTML5 (1991-2017): Standardisierung durch W3C und WHATWG.
- CSS3 (1996-2011): Standardisierung durch W3C.
- ES6 (1997-2023 (JETZT)): Standardisierung durch Ecma International mit jährlichen Updates.

### Browser

- **Erste Webbrowser:** WorldWideWeb 1990 (später Nexus)
- **Standards:**
  - HTTP (Tim Berners-Lee, 1989) & FTP (1971)
  - HTML (1990)
- **Herausforderungen:**
  - Browser-Kompatibilität ([caniuse](https://caniuse.com))
    - WorldWideWeb funktionierte nur auf dem NeXTSTEP-Betriebssystem
  - Responsiveness
    - WorldWideWeb konnte nicht einmal Grafiken anzeigen und öffnete diese in einem anderen Programm.

#### Browser - Statistiken

- **Chrome-Monopol:**
  - Etwa 67 % Marktanteil!
- **Forderungen des US-Justizministeriums:**
  - Verkauf von Chrome und Verbot ausschließender Verträge.
  - Keine Bevorzugung eigener Dienste.
- **Potenzielle Konsequenzen:**
  - Chrome-Verkaufswert: $20 Mrd.
  - Mögliches 5-jähriges Verbot der Browsermarkt-Teilnahme für Google.
  - Entscheidung im Spätsommer 2025 erwartet.

### Die Pioniere der Suchmaschinen

- **Archie (1990)**: Erste Suchmaschine.
  - durchsuchte FTP-Server nach Dateinamen und Meta-Daten.
- **Lycos (1994)**: durchsuchte Dokumente und ermittelte die Häufigkeit von Suchbegriffen
- **Google (1998)**: revolutionierte den Markt mit überlegener Relevanz und Geschwindigkeit

## Das Framework Massacre.

- **jQuery** (2006): einfachere DOM-Manipulation.
- **AngularJS** (2010): Neuer Ansatz für SPAs.
- **React** (2013): entwickelt von Facebook (eigentlich Library).
- **Vue** (2014): Leichtgewichtige Alternative (Busproblem).
- **Svelte** (2016): Kompiliert zur Build-Zeit, keine Laufzeitbibliothek, hohe Performance. (eigentlich Compiler)

### Back to the Roots: SSR und HTMX

SSR ist wieder im Aufschwung und SPAs gehören mittlerweile größtenteils der Vergangenheit an.

## Zukunft - Webentwicklung Heute

### Serverless

- Wartung und
- Skalierung übernimmt ein PaaS

### WebAssembly

- seit 2015
- Kompilierung von effizienten Sprachen in Browser-lesbares Format

### PWAs

- Website kann von der Website aus installiert werden.
- Website funktioniert auch offline.

### Neue Toolchains (jetzt auch schnell)

- Bun (Zig)
- Deno (Rust)
- VoidZero (Typescript und Rust)
