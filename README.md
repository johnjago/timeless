# Timeless — a blog theme for Hugo

Timeless is an opinionated design that emphasizes reading experience and
content above all else.

## config.toml

```
baseURL = "/"
languageCode = "en-us"
title = "Blog"
theme = "timeless"

[params]
  description = "A blog about things."
  footerSymbol = "~"
  allPostsText = "all posts"
  serif = true

[menu]
  [[menu.main]]
    name = "Link 2"
    url = "about"
    weight = 2
  [[menu.main]]
    name = "Link 3"
    url = "https://example.com"
    weight = 3
```

## License

MIT
