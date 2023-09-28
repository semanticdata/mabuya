<p align="right">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-tale" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-tale" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-tale" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-tale" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/zola-tale.svg" />
</p>

# Zola Tale

Check out a live [Demo](https://semanticdata.github.io/zola-tale/) of the theme.

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
git clone git@github.com:semanticdata/zola-tale.git
cd zola-tale
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

Aiming for perfect [Lighthouse](https://pagespeed.web.dev/) scores in all categories. See the latest [scores](https://pagespeed.web.dev/analysis/https-semanticdata-github-io-zola-tale/0jg8x3evtr?form_factor=mobile).

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

Aiming for high scores in [GTMetrix](https://gtmetrix.com/). See the latest [performance report](https://gtmetrix.com/reports/semanticdata.github.io/uGxgzR0q/).

- Performance: 100%
- Structure: 100%
- Total Website size: 64KB compressed, 78KB uncompressed.
- Largest Contentful Paint:[^1] 287ms.
- Total Blocking Time:[^2] 0ms.
- Cumulative Layout Shift:[^3] 0.01.

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Tale-Zola**. Please
search [existing issues](https://github.com/semanticdata/zola-tale/issues). It’s
possible someone has already reported the same problem.

If your problem or idea is not addressed yet, [open a new issue](https://github.com/semanticdata/zola-tale/issues/new).

## Contributing

We'd love your help! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) to learn
about the kinds of contributions we're looking for.

## Acknowledgements and Attributions

Zola Tale is based on [Tale-Zola](https://github.com/aaranxu/tale-zola), a port of the Jekyll theme [Tale](https://github.com/chesterhow/tale).

The icons used are part of [UXWing](https://uxwing.com/license/)'s collection.

## License

Source code is available under [MIT](LICENSE).

[^1]: For a good user experience, aim for an LCP of 1.2 seconds or less.
[^2]: For a good user experience, aim for a TBT of 150 milliseconds or less.
[^3]: For a good user experience, aim for a CLS score of 0.1 or less.
