# Minimal `jekyll-theme-minimal` gem

### Fabio Massacci

This theme was ported from the GitHub Automatic Page Generator to a Jekyll v3.3 theme gem.

To use it on a Pages site, add `theme: jekyll-theme-minimal` to your `_config.yml`.

```yml
theme: jekyll-theme-minimal
title: Custom title
description: Custom description.
show_downloads: true
google_analytics:
```

- To override the repository name or description from GitHub used in the header, set a `title` or `description`.
- Set `show_downloads` to `false` to hide the download buttons in the header.
- Set `google_analytics` to your tracking ID to enable pageview tracking.

This theme includes a single `default` layout. Markdown files should be prefixed with the following frontmatter.

```
---
layout: default
---
```

#### CSS

For CSS customization, create your own `/assets/css/styles.scss` in your project to replace the one from this theme, and override selected stylesheet properties.

```scss
---
---
@import "fonts";
@import "rouge-github";
@import "minimal";
```

#### Syntax Highlighting

[Rouge](http://rouge.jneen.net/) is the default highlighter in Jekyll 3. This theme includes the `github` stylesheet from Rouge.


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/FabioMassacci/fabiomassacci.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Prova
## Trial 2
### Trail 3 3

- Bulleted
- List

1. Numbered
2. List

**This is Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FabioMassacci/fabiomassacci.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Copyright
This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License (CC-A-SA-3.0)
To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/3.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.


