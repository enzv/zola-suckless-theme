+++
title = "Markdown Syntax Guide"
date = 2019-03-11
tags = ["demo"]
+++

# Markdown Syntax Guide

This page is the broad markdown sample.
It shows the common syntax in one place so the theme has something real to render.
If it breaks here, it was never a theme.
The point is coverage, not decoration.
If you can break this page, you can probably break the rest.

## Headings

# H1
## H2
### H3

## Emphasis

**bold text**

*italic text*

`inline code`

## Quote

> A theme should make text easy to read before it tries to look clever.

## Lists

1. First item
2. Second item
3. Third item

- First item
- Second item
- Third item

- [x] Finished item
- [ ] Unfinished item

## Extended Syntax

### Footnote

Here is a sentence with a footnote.[^1]

[^1]: This is the footnote.

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the page
- [ ] Check the output
- [ ] Leave the fluff out

### Emoji

That still reads fine with `🙂` in the page.

## Code

```sh
zola build
zola check
```

## Rule

---

## Links

[About](/about/)

## Image

![Logo](/logo.svg)

## Table

| Syntax | Meaning |
| --- | --- |
| H1 | Section title |
| Code | Literal text |
| Table | Structured content |

## More Text

The point is not decoration.
The point is that longform text, lists, links, code, tables, and images all stay readable when the page gets busy.

This is also a good place to check spacing, line length, and how the theme handles plain paragraphs without trying to turn them into cards.
