<p align="right">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/mabuya" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/mabuya" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/mabuya.svg" />
</p>

# Mabuya

Mabuya is a minimal Zola theme with the goal of helping you build a light and SEO-ready blog.

Check out a live [Demo](https://semanticdata.github.io/mabuya/) of the theme.

Mabuya is named as such after [Mabuya hispaniolae](https://en.wikipedia.org/wiki/Mabuya_hispaniolae?useskin=vector), possibly extinct[^1] species of skink endemic to the Dominican Republic.

## Features

While working on the theme, I have made a few changes. Here's a short non-conclusive list:

- Refactored stylesheets.
- Added Dark mode and its switch.
- Added working GitHub Workflow.
- New style variables file.
- Other Quality of Life improvements.

## Requirements

Before using the theme, you need to install the [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.17.2.

## Quick Start

```bash
git clone git@github.com:semanticdata/mabuya.git
cd mabuya
zola serve
# open http://127.0.0.1:1111/ in the browser
```

## Customization

You can customize your configurations, templates and content for yourself. Look
at the `config.toml`, `theme.toml` and templates files in this repo for an idea.

In most cases you only need to modify the content in the `config.toml` file to
custom your blog, including different expressions in your speaking language.

### Custom CSS styles

Adding your custom css is as easy as adding your own styles to the `sass/_custom.scss` file.

## Useful Commands

| Command                    | Description                |
| -------------------------- | -------------------------- |
| `zola build`               | Build only                 |
| `zola serve`               | Build and Serve            |

## Lighthouse Scores

Aiming for perfect [Lighthouse](https://pagespeed.web.dev/) scores in all categories.

### Desktop

- [x] Performance: 100 / 100
- [ ] Accesibility: 93 /100
- [x] Best Practices: 100 /100
- [x] SEO: 100 /100

### Mobile

- [ ] Performance: 93 / 100
- [ ] Accesibility: 93 /100
- [x] Best Practices: 100 /100
- [x] SEO: 100 /100

## GTMetrix Scores

Aiming for high scores in [GTMetrix](https://gtmetrix.com/).

- Performance: 100%
- Structure: 100%
- Total Website size: 64KB compressed, 78KB uncompressed.
- Largest Contentful Paint:[^2] 287ms.
- Total Blocking Time:[^3] 0ms.
- Cumulative Layout Shift:[^4] 0.01.

## Reporting Issues

We use GitHub Issues as the official bug tracker for **Mabuya**. Please
search [existing issues](https://github.com/semanticdata/mabuya/issues). It’s
possible someone has already reported the same problem.

If your problem or idea is not addressed yet, [open a new issue](https://github.com/semanticdata/mabuya/issues/new).

## Contributing

We'd love your help! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) to learn
about the kinds of contributions we're looking for.

## Acknowledgements and Attributions

Mabuya is a fork of [Tale](https://github.com/aaranxu/tale-zola), a port of the Jekyll theme [Tale](https://github.com/chesterhow/tale).

The icons used are part of [UXWing](https://uxwing.com/license/)'s collection.

## License

Source code is available under [MIT](LICENSE).

[^1]: *Mabuya hispaniolae*'s conservation status is *Critically endangered, possibly extinct*.  
[^2]: For a good user experience, aim for an LCP of 1.2 seconds or less.  
[^3]: For a good user experience, aim for a TBT of 150 milliseconds or less.  
[^4]: For a good user experience, aim for a CLS score of 0.1 or less.  
