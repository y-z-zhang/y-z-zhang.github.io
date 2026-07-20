# y-zhang.com

Personal academic website of [Yuanzhao Zhang](https://y-zhang.com) — Simons Empire
Assistant Professor of Physics & Astronomy at the University of Rochester.

Built with [Jekyll](https://jekyllrb.com) on a customized
[Forty](https://html5up.net/forty) theme (HTML5 UP, CCA 3.0 license), deployed via
GitHub Pages.

Companion site: [AID Lab](https://lab.y-zhang.com) (research group), maintained in
[y-z-zhang/aid-lab](https://github.com/y-z-zhang/aid-lab).

## Structure

- `index.md` — homepage bio and research questions
- `publications.md` — selected publications (full list on the lab site)
- research theme pages (`machine-learning.md`, `higher-order-interactions.md`,
  `network-dynamics.md`, `basins.md`) — homepage tiles, one per area
- `photos.md` — photo gallery (WebP derivatives in `assets/images/personal/`)
- `_config.yml` — site settings and profile links

## Local development

```sh
bundle install
bundle exec jekyll serve
```
