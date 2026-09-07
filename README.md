# easter — Easter Production Handbook

A data-only site rendered by the shared **AutoCSS** front-end. This repo ships only
its own `index.html` (a thin shell that links the shared assets from
`Autocss-com/cdn` by absolute URL) and its content as `assets/data/*.json`. No
build, no framework, no third-party dependencies.

- Front-end (HTML shell behaviour, CSS runtime, JS data-transport, the component
  pool, service worker): **`Autocss-com/cdn`**, linked by URL.
- Content source: the **`D7460N/EASTER`** handbook (introduction, roles, basics,
  rehearsal, production, ministry, glossary), authored here as JSON contracts.

Nav = HOME + the seven handbook sections + FAQ. Each page stacks its section's
docs as text (headings, paragraphs, lists; tables flattened to lists). The
pool-violation notice and its FAQ link come from the shared front-end.

Live: https://autocss-com.github.io/easter/
