---
title       : Um teste com slidify
subtitle    : Exemplos
author      : Fernando Mayer
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

Texto do slide 2

---

## Slide 3

Texto do slide 3


```r
rnorm(10)
```

```
##  [1]  1.937393438  0.149259103  2.075743068  0.543308827 -0.315728962
##  [6] -0.007401945  0.293363473  0.817748983 -0.671538346  0.971765973
```

---

## Slide 4


```r
plot(rnorm(100))
```

![plot of chunk figura](assets/fig/figura-1.png) 

---

## Slide 5

```shell
ls
```
