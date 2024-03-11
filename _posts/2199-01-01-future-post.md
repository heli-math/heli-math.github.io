---
title: 'Template for my blog'
date: 2024-03-11
permalink: /posts/2024/03/template/
tags:
  - markdown
  - hide
---

This post will show up by default. To disable scheduling of future posts, edit `config.yml` and set `future: false`. 

# Heading

```
# Heading level 1
## Heading level 2
### Heading level 3
```

# code

```R
# This is a sample R code block
install.packages("ggplot2")
library(ggplot2)

# Create a simple scatter plot
ggplot(data = mtcars, aes(x = wt, y = mpg)) + 
    geom_point()
```
