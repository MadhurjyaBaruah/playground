# Geist Pixel — Type Specimen

**[Live demo ↗](https://madhurjyabaruah.github.io/playground/vercel-pixel-font/)**

An interactive, self-contained specimen page for [Geist Pixel](https://vercel.com/font?type=pixel), Vercel's variable pixel typeface. Switch between all five shapes live, type your own text into the playground, and browse the full glyph set — all rendered in the real font, with no external requests.

> Not an official Vercel product — just an independent showcase.

[![Website Preview](https://api.microlink.io/?url=https://madhurjyabaruah.github.io/playground/vercel-pixel-font/&screenshot=true&meta=false&embed=screenshot.url)](https://madhurjyabaruah.github.io/playground/vercel-pixel-font/)

## Features

- **Shape switcher** — toggle the whole page between Square, Circle, Grid, Triangle, and Line, the five stops on Geist Pixel's `ELSH` variable axis
- **Live playground** — type anything and watch it render live in the selected shape
- **Glyph specimen board** — uppercase, lowercase, numerals, and symbols, laid out like a real type specimen sheet
- **Spec sheet** — weight, axis, license, and install snippets
- Zero dependencies, zero build step, zero external font requests — every font file is embedded as base64 directly in the HTML

## Usage

Self-contained single file — open `index.html` in any browser, no build step or server required.

This copy is deployed straight from this folder via GitHub Pages — that's what's running at the live demo link above.

## How it's built

Plain HTML, CSS, and vanilla JS — no framework, no bundler, no npm install required to run it. The five Geist Pixel shape files (`Square`, `Circle`, `Grid`, `Triangle`, `Line`) plus variable-weight Geist Mono are sourced from Vercel's official [`geist`](https://www.npmjs.com/package/geist) npm package, base64-encoded, and inlined as `@font-face` rules — so the page renders correctly offline, with no CDN dependency or flash of fallback type.

## Credits

Geist Pixel is designed and released by **Vercel**, part of the wider Geist typeface family (Sans / Mono / Pixel).

- Official font page: https://vercel.com/font?type=pixel
- npm package: https://www.npmjs.com/package/geist
- Source & releases: https://github.com/vercel/geist-font

## License

- **This repo's code** — no license set yet; add whichever you prefer (MIT is a common default for a small demo like this).
- **Geist Pixel font** — SIL Open Font License 1.1. Free to use, including embedded in projects like this one. Full text: https://github.com/vercel/geist-font/blob/main/LICENSE.txt
