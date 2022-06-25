# Pandoc-Lua-Markdown-Bootstrap-

Project of creating a Lua filter to converts markdown to Bootstrap components.

# Headers

A title followed by a paragraph a line and another paragraph
```
# title
Lead text
---
Description
```

Should be converted into a "jumbotron" (bootstrap 4) or a header (Bootstrap 5).


# Carousel
A section called carousel with multiple Headers should be converted into a carousel, each header becoming a slide.

```
::: carousel

# first slide
Some text

# Second slide
Some text

:::

```

# Quiz
A heading with a list inside a Quiz section should be converted into a quiz

```
::: quiz

# question 1

* proposition a
* proposition b
  * feedback for proposition b
* proposition c
* proposition d
  * feedback for proposition d

:::
```
