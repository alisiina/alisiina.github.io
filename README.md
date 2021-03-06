[![website-status](https://img.shields.io/website-up-down-green-red/https/sinablk.github.io.svg?style=flat)](https://sinablk.github.io) ![last-commit](https://img.shields.io/github/last-commit/sinablk/sinablk.github.io.svg?colorB=blue&style=flat) ![size](https://img.shields.io/github/repo-size/sinablk/sinablk.github.io.svg?colorB=red&style=flat) [![jekyll-gem](https://img.shields.io/gem/v/jekyll.svg?colorB=blueviolet&label=jekyll&style=flat)](https://rubygems.org/gems/jekyll/versions/3.8.5)

# [sinablk.github.io](https://sinablk.github.io)

> Personal Jekyll website. Published on Github Pages

### Note to self

- Use `jekyll serve --drafts` to view posts in `_drafts` folder on `localhost`.
- Read more into the [Jekyll Feed](https://github.com/jekyll/jekyll-feed) plugin.

### Issues

- The social sharing links haven't been fully tested.
- Sizing is mostly in `px`. Should change to the more robust `rem` and `em` where possible.

### Plugins used

- `jekyll-paginate` v1.1.0
- `jekyll-seo-tag` v2.5.0
- `jekyll-feed` v0.11.0
- Search powered by [Lunr.js](https://lunrjs.com/)
- Comments powered by [JustComments](https://just-comments.com/)

### Directory tree

```
.
├── _drafts
|   └── . . .
├── _includes
|   ├── analytics.html
|   ├── footer.html
|   ├── head.html
|   ├── header.html
|   ├── mathjax.html
|   └── socialsharing.html
├── _layouts
|   ├── default.html
|   ├── home.html
|   ├── page.html
|   └── post.html
├── _posts
|   └── . . .
├── _sass
|   ├── styles
|   |    ├── _base.scss
|   |    ├── _layout.scss
|   |    ├── _mobile-dropdown.scss
|   |    ├── _pagination.scss
|   |    ├── _search.scss
|   |    ├── _sharebuttons.scss
|   |    ├── _syntax-highlighting-monokai.scss
|   |    └── _syntax-highlighting.scss
|   └── style.scss
├── about
|   └── index.md
├── assets
|   ├── js
|   |    ├── search.js
|   |    └── smoothscroll.js
|   ├── apple-touch-icon.png
|   ├── favicon.png
|   └── main.scss
├── images
|   └── . . .
├── search
|   └── index.html
.
.
.
├── 404.html
└── index.html
```
