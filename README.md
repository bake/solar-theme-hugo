# Solar Theme for Hugo

A minimalistic theme for [Hugo](https://gohugo.io/) blogs, fork of
[Solar Theme for Ghost](https://github.com/mattvh/solar-theme-ghost).

It offers three color schemes: (Monokai) `light`, (Monokai) `dark` and `gray`
(default). Additional HTML can be injected just before `</head>` and `</body>`
by creating a `head.html` or `foot.html` inside `layouts/partials/`. The default
(empty) logo can be overwritten by creating a `logo.svg` in `static/img/`.

## Screenshot

![Screenshot](/images/screenshot.png)

## Installation

Same as with any other theme:

```bash
$ git clone https://github.com/bake/solar-theme-hugo.git themes/solar-theme-hugo
$ hugo server --theme=solar-theme-hugo
...
```

## License

GPLv2 or higher
