## Posts
Add posts to the `_posts/` folder. Their titles should be `YEAR-MONTH-DATE-MY-TITLE.md`

View the table of contents [example](https://github.com/Hoenn/hoenn.github.io/blob/master/_posts/2018-07-16-table-of-contents.md) 

## Pages
Add pages to the `_pages/` folder. They will appear at the top navigation bar if and only if:

This block is present at the top of `_pages/example-page.md`

```yaml
---
layout: single
title: "Example-Page"
permalink: /example-page/
author_profile: true
---
```

And the page is added to `_data/navigation.yml`
```yaml
main:
  - title: "About"
    url: /about/
  - title: "Resume"
    url: /resume/
  - title: "Example-Page"
    url: /example-page/
```

