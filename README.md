<p align="right">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/mabuya" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/mabuya.svg" />
</p>

# Mabuya

Mabuya is a minimal Zola theme focused on helping you build an elegant, light, and SEO-ready blog.

Check out the live [Demo](https://semanticdata.github.io/mabuya/) of the theme.

Mabuya is named as such after the [Mabuya hispaniolae](https://en.wikipedia.org/wiki/Mabuya_hispaniolae?useskin=vector), a possibly extinct[^1] species of skink endemic to the Dominican Republic my home country.

## Features (*out-of-date*)

While working on the theme, I have added new functionality and quality of life improvements. Here's a short non-conclusive list:

- Fully refactored stylesheets.
- Added Dark theme and color scheme toggle.
- Added new footer navigation.
- Created a custom GitHub Action that is faster than any other in GitHub.
- Refined page transitions from desktop to mobile and viceversa.
- Centralized custom variables. Made it easier to make color changes to the site.
- Addressed PR [#7](https://github.com/aaranxu/tale-zola/pull/7).
- Addressed (temporarily) Issue [#1](https://github.com/aaranxu/tale-zola/issues/1).
- Addressed Issue [#4](https://github.com/aaranxu/tale-zola/issues/4).
- Optimized for speed and Accesibility. Showcased by the perfect Lighthouse scores across the board.
- Many other small improvements.

## Lighthouse Scores

Perfect [Lighthouse](https://pagespeed.web.dev/) scores in all categories.

### Mobile

- [x] Performance: 100 / 100
- [x] Accesibility: 100 /100
- [x] Best Practices: 100 /100
- [x] SEO: 100 /100

### Desktop

- [x] Performance: 100 / 100
- [x] Accesibility: 100 /100
- [x] Best Practices: 100 /100
- [x] SEO: 100 /100

## Screenshots (*out-of-date*)

| Desktop | Mobile |
| :-----: | :----: |
| ![website screenshot](screenshots/screenshot-index-dark.png) | ![website screenshot](screenshots/screenshot-mobile.png) |

## Requirements

Before using the theme, you need to install [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.17.2.

## Quick Start

```bash
git clone git@github.com:semanticdata/mabuya.git
cd mabuya
zola serve
# open http://127.0.0.1:1111/ in the browser
```

## Customization

You can customize configurations, templates and content yourself. Look at the `config.toml`, and templates files for an idea.

In most cases you only need to modify the contents of `config.toml` to
customize your blog.

### Custom CSS styles

Adding custom css is as easy as adding your styles to `sass/_custom.scss`.

## Useful Commands

| Command                    | Description                |
| -------------------------- | -------------------------- |
| `zola build`               | Build only                 |
| `zola serve`               | Build and Serve            |

## GTMetrix Scores

Aiming for high scores in [GTMetrix](https://gtmetrix.com/).

- Performance: 100%
- Structure: 100%
- Total Website size: 33.4KB compressed, 48.2KB uncompressed.
- Largest Contentful Paint:[^2] 238ms.
- Total Blocking Time:[^3] 0ms.
- Cumulative Layout Shift:[^4] 0.

## Reporting Issues

We use GitHub Issues as the official bug tracker for **Mabuya**. Please
search [existing issues](https://github.com/semanticdata/mabuya/issues). It’s
possible someone has already reported the same problem.

If your problem or idea is not addressed yet, [open a new issue](https://github.com/semanticdata/mabuya/issues/new).

## Contributing

We'd love your help! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) to learn
about the kinds of contributions we're looking for.

## Acknowledgements and Attributions

Mabuya is a fork of [Tale](https://github.com/aaranxu/tale-zola), which is a port of the Jekyll theme [Tale](https://github.com/chesterhow/tale).

The icons used throughout the site are provided by  [UXWing](https://uxwing.com/license/).

## License

Source code in this repository is available under the [MIT](LICENSE) license. You are free to use this code however you see fit. that said, some acknowledgement would be well received.

[^1]: *Mabuya hispaniolae*'s conservation status is *Critically endangered, possibly extinct*.  
[^2]: For a good user experience, aim for an LCP of 1.2 seconds or less.  
[^3]: For a good user experience, aim for a TBT of 150 milliseconds or less.  
[^4]: For a good user experience, aim for a CLS score of 0.1 or less.  
