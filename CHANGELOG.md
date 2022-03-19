# Changelog

## 0.12.1 (2022-03-19)

### Added
- Show post dates in Chinese if the `defaultContentLanguage` param is set to
  `zh`

### Changed
- Use the full text of the post in the RSS feed item description for easy
  reading in RSS readers
- The background color is #fffcf9, a light beige that is brigher, less gloomy,
  and more interesting than the previous light gray

## 0.12.0 (2021-08-26)

### Changed
- Post date is now in ISO 8601
- Revised 404 page text

## 0.11.0 (2021-05-24)

### Added
- Ability to change the "all posts" text that shows up at the top of single
  posts and pages through the `headerAllPostsText` param

## 0.10.0 (2021-05-17)

### Changed
- Make the body narrower for a cozy feeling
- Allow code blocks to expand beyond the article width to reduce the need to
  side scroll

## 0.9.0 (2021-05-08)

### Added
- A link back to home from a single page (like an about page)

## 0.8.0 (2021-04-07)

### Added
- The menu links defined in `menu.main` in config.toml are also shown in the
  home page header
- The site title on the home page now links to `/`
- Italic text for blockquotes to better set them apart from the body text

## 0.7.0 (2021-04-05)

### Changed
- Make link styles more "timeless" (standard color, subtle hover effects)

## 0.6.0 (2021-03-18)

### Changed
- Place `meta charset` at the top of `<head>` to make sure the title is always
  rendered correctly: https://stackoverflow.com/a/5573544
- Use the pipe symbol `|` as the title separator

## 0.5.0 (2021-03-14)

### Added
- CSS styles for bold and italic text

## 0.4.0 (2021-03-02)

### Added
- Ability to turn off the serif fonts (currently only Charter) with the
  `serif` param, which will cause the site to fall back to a sans-serif
  system font stack

## 0.3.0 (2021-02-25)

### Added
- Full date in the title attribute of dates displayed as only the month and year

## 0.2.0 (2021-01-03)

### Changed
- More obvious link highlight upon hover
- Darker "light" text for AAA accessibility

### Fixed
- Don't assume that the base URL is /

## 0.1.0 (2021-01-02)

### Added
- Release initial version of the theme
