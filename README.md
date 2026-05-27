# Projects Overview

Live overview на всички dashboard-и и изследователски проекти на [@tsvetoslavtsachev](https://github.com/tsvetoslavtsachev).

Single-page HTML, hostnat на GitHub Pages. Status badge-ите се обновяват автоматично от GitHub Actions API през [shields.io](https://shields.io) — reload-ни страницата за пресни данни.

## Секции

- **Live dashboards** — ETF · Stock Selection · SP500/STOXX Momentum · SP500/STOXX Rotation · COT Monitor · COT CTA
- **Macro briefings — US · EU · China** — седмични briefing pipelines (FRED / ECB+Eurostat / akshare)
- **Data layer & aggregation** — `macro-satellite` (агрегатор, in development) · `vrm-state` (data input)

## Структура

- `index.html` — целият dashboard
- `.github/workflows/deploy-pages.yml` — auto-deploy при push към `main`

## Live URL

След като създадеш repo `projects-overview` в GitHub и enable-неш Pages (Settings → Pages → Source: GitHub Actions):

`https://tsvetoslavtsachev.github.io/projects-overview/`
