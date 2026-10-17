# HTML Tags

A hands-on reference of **67 HTML tags**. Every tag comes with a plain-English explanation, a live example rendered by your browser, and a **Show code** button that reveals the exact HTML behind it.

I first built this page in 2017 while learning HTML. In 2026 it got a full refresh.

## Features

- **67 tags in 11 groups:** page structure, metadata, sections, grouping content, text, edits, images and media, tables, forms, interactive elements and scripting
- **Live examples** for every tag that can be shown on a page, and code snippets for the ones that live in `<head>`
- **Show code** and **Copy code** on every example
- **Search** by tag name or description (press `/` to jump to the search box) and **filter** by group
- **Responsive:** works on phones, tablets and desktops, with light and dark mode
- **No frameworks, no build step:** plain HTML, CSS and JavaScript in one file

## Run it locally

```bash
git clone https://github.com/Hasanahammad/html_Tags.git
cd html_Tags
```

Then open `index.html` in any modern browser.

## What changed in the 2026 update

- Fixed invalid HTML: unclosed headings, a broken `cite` tag and invalid `colgroup` styles
- Corrected wrong examples: `area` now shows a real clickable image map, `link`, `base` and `cite` show proper usage, `figure` now wraps its image and caption, and the `article` example has accurate facts
- Filled in the examples that only said "null" (`meta`, `blockquote`, `ul`, `div`, `main`)
- Replaced the pop-up `alert()` on page load with a click-triggered `script` demo
- Added 17 common tags: `span`, `br`, `mark`, `code`, `kbd`, `iframe`, `svg`, `th`, `label`, `input`, `button`, `select`, `textarea`, `details`, `summary`, `dialog` and `canvas`
- New responsive layout with search, group filter and a code viewer

## Project files

| File | What it is |
|---|---|
| `index.html` | The whole page: markup, styles and scripts |
| `a.jpg`, `b.jpg` | Images used in the `img`, `figure`, `figcaption` and `area` examples |
| `*.mp4`, `*.mp3` | Media used in the `video` and `audio` examples |

## Author

**Hasan Ahammad**, Senior Software Engineer, Dhaka, Bangladesh

[GitHub](https://github.com/Hasanahammad) | [LinkedIn](https://linkedin.com/in/hasancseit)
