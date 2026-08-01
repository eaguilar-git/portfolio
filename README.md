# Portfolio

Source for my personal site.

**Live: https://eaguilar-git.github.io/portfolio/**

I'm an energy economist and quantitative analyst based in Washington, DC, working on power
market design, tariff and cost-of-service regulation, cross-country utility data, and the
macroeconomics of electricity. The site sets out the argument I work on and catalogues what
I've built, with links to the public pieces.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The entire site. One file. |
| `og-image.jpg` | Social preview card, 1200x630. Referenced by the page's Open Graph tags, not by the page itself. |

## How it's built

Plain HTML and CSS in a single file, deliberately.

- **No dependencies.** No CDN, no framework, no web font, no build step, no package manager.
  Nothing to install and nothing to break. The page renders correctly offline and on
  locked-down corporate networks, which is where it tends to get opened.
- **Images are embedded** as base64 data URLs, so the page is genuinely self-contained. The
  whole thing is about 77 KB.
- **Dark mode** via `prefers-color-scheme`, both themes tested.
- **Responsive**, verified with no horizontal overflow at 320, 390, and 430 pixels wide.

There is no toolchain here because the page doesn't need one. A static document that will be
read and not much changed is a case where the simplest thing that works is also the most
durable.

## Some of the public work linked from the site

- [Global Power Market Structures Database](https://www.worldbank.org/en/programs/global-power-market-structures),
  World Bank. I built the Power BI platform.
- [Portal de Pérdidas](https://potenciahonduras.asjhonduras.com/portal-perdidas/),
  Potencia Honduras. Geospatial grid loss analysis.
- [Master's research](https://github.com/eaguilar-git/Master-s-Final-Paper): efficiency
  benchmarking and difference-in-differences across 62 utilities in 49 countries, in Python.

## Deploying

GitHub Pages serves this from the `main` branch, root folder. Any commit to `index.html`
republishes in about a minute.

## Contact

[aguilared.96@gmail.com](mailto:aguilared.96@gmail.com) ·
[linkedin.com/in/aguilared](https://linkedin.com/in/aguilared)
