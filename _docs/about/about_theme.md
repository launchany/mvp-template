---
title: About this theme
permalink: /docs/about_theme/
---

This Jekyll documentation theme was developed by [Can Güney Aksakalli](https://aksakalli.github.io).

The GitHub repo for this documenation theme is [https://github.com/aksakalli/jekyll-doc-theme](https://github.com/aksakalli/jekyll-doc-theme).

### Theme options

By default, this website uses `flatly` theme, but you can change it to another [bootwatch theme](https://bootswatch.com/) by setting `bootwatch` variable in `_config.yml` file.

Don't forget to restart `Jekyll` if you are running locally because the configuration is not re-read upon change.

### Customization

This template uses [bootstrap-sass](https://github.com/twbs/bootstrap-sass) along with [bootwatch themes](https://bootswatch.com/). You can create your own theme by writing your own `sass` files.

Create a new a theme folder like `_sass/bootwatch/custom` and set your `bootwatch` variables in `_config.yml` to `custom`:

```yaml
bootwatch: custom
```

