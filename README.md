# Solar Theme for Hugo

A minimalistic theme for [Hugo](https://gohugo.io/) blogs, fork of
[Solar Theme for Ghost](https://github.com/mattvh/solar-theme-ghost).

It offers three color schemes: (Solarized) `light`, (Solarized) `dark` (default)
and `gray`. Additional HTML can be injected just before `</head>` and `</body>`
by creating a `head.html` or `foot.html` inside `layouts/partials/`. The default
(empty) logo can be overwritten by creating a `logo.svg` in `static/img/`.

## Screenshot

![Screenshot](/images/tn.png)

## Syntax Highlighting

This theme does not bring a syntax highlighter. If you want to use
[Hugos](https://gohugo.io/content-management/syntax-highlighting/), remember to
update the color scheme by [setting pygmentsStyle](/exampleSite/config.toml#L4).
The pygments style `solarized-dark`, for example, matches the themes `dark`
color scheme, while `solarized-light` matches `light` and `solarized-dark256`
works with `gray`. Otherwise, the necessary JavaScript can be placed inside
`static/` and get included by providing a `footer.html` as described above.

## Installation

Same as with any other theme:

```bash
$ git clone https://github.com/bake/solar-theme-hugo.git themes/solar-theme-hugo
$ hugo server --theme solar-theme-hugo
...
```

## License

GPLv2 or higher
