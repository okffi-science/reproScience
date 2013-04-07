---
title       : Reproducible research
subtitle    : Concepts and tools
author      : Joona Lehtomäki
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
--- &image

<img src="http://www.phdcomics.com/comics/archive/phd101212s.gif" class="centered-img"></img>

---

## Slide 2

> 1. Point 1
> 2. Point 2
> 3. Point 3

---

## Some R-code


```r
# Quick summary
library(ggplot2)
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```

--- &notitle


```r
# Quick plot of the data
qplot(speed, dist, data = cars) + geom_smooth()
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

