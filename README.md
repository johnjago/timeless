# Timeless — a blog theme for Hugo

**Note**: As of June 2023, I stopped sharing this theme between my two blogs, [johnjago.com](https://johnjago.com) and [gaozhang.co](https://gaozhang.co). Letting each theme evolve on its own allows it to better fit the needs of each blog and greatly simplifies the development workflow for editing the themes.

---

Timeless is an opinionated design that emphasizes reading experience and
content above all else.

It supports both `en` and `zh` content language, including regional date
formats. It will default to English; otherwise you can add
`defaultContentLanguage = "zh"` to config.toml.

This theme is designed for my particular needs, so it may not be suitable for
any new Hugo blog.

## config.toml

```
baseURL = "/"
languageCode = "en-us"
title = "Blog"
theme = "timeless"

[params]
  description = "A blog about things."
  headerAllPostsText = "all posts"
  footerSymbol = "~"
  allPostsText = "read more"
  serif = true
  script = '<script src="https://example.org/example.js" defer></script>'

[menu]
  [[menu.main]]
    name = "Link 1"
    url = "about"
    weight = 1
  [[menu.main]]
    name = "Link 2"
    url = "https://example.com"
    weight = 2
```

## License

MIT
