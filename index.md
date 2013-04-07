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

--- #aboutme bg:url(assets/img/spaghetti.jpg) bg-repeat:no-repeat bg-position:center

--- #content &vcenter

## Content

## 1. Background
## 2. Concepts
## 3. Tools: RStudio and Git

--- #motivation1

## Slide 2

> 1. Point 1
> 2. Point 2
> 3. Point 3

--- #motivation2

--- #open-science &twocol w1:50% w2:50%

## Open science

"Opening up access to the data and software, not just the final publication, is one of goals of the open science movement" <br />(Ram, 2013)

*** left
- Open access
- Open data
- Open notebook science
- Open source software

*** right

<img src="http://upload.wikimedia.org/wikipedia/commons/b/bb/Open_Science_Logo.jpg" class="centered-img" style="max-height:50%;" title="By G.emmerich (Own work) CC-BY-SA-3.0, via Wikimedia Commons"></img>

--- &notitle bg:black

<img src="http://bit.ly/10FmaGf" class="centered-img" title="By G.emmerich (Own work) CC-BY-SA-3.0, via Wikimedia Commons"></img>

--- #concepts

## Reproducibility

> * With replication, independent investigators address a scientific hypothesis and build up evidence for or against it (Peng, 2011)
> * Allows others to build upon existing work and use it to test new ideas and develop methods (Ram, 2013)
> * While currently there is unilateral emphasis on "first" discoveries, there should be as much emphasis on replication of discoveries (Ioannidis, 2005)

--- #problems1 

<img src="assets/img/wolkowich_et_al_data_sharing.png" class="centered-img" title="Wolkowich et al. 2012"></img>

Wolkovich et al. (2012)

--- #problems2

<img src="assets/img/peng_comp_repro.png" class="centered-img" title="Peng 2011"></img>

Peng 2011

--- #problems3

<img src="assets/img/morris_and_wills_nature1.png" class="centered-img" title="Mounce and Willis 2011"></img>

<img src="assets/img/morris_and_wills_nature2.png" class="centered-img" title="Mounce and Willis 2011"></img>

Mounce and Willis (2011)

--- #problems4

<img src="assets/img/van_noorden_nature.png" class="centered-img" title="van Noorden 2011"></img>

van Noorden 2011

--- #problems5

<img src="assets/img/sirkia_et_al_workflow.png" class="centered-img" style="margin-left: 0; float: left;" title="Sirkiä et al. 2012"></img>

Sirkiä et al. 2012

--- #problems6

<iframe src="http://bit.ly/10FnSHI"></iframe>

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


--- &image

<img src="http://www.phdcomics.com/comics/archive/phd101212s.gif" class="centered-img"></img>

--- 

## Git: steep learning curve?

<img src="http://d22zlbw5ff7yk5.cloudfront.net/images/cm-27811-1508860c9c2366.gif" class="centered-img" style="margin-top: 150px;"></img>

--- #reference

### Reference:
<div class="reference">
[1] Ram K. (2013): Git can facilitate greater reproducibility and increased transparency in science. Source Code for Biology and Medicine [Internet]. [cited 2013 Mar 1];8(1):7. Available from: http://www.scfbm.org/content/8/1/7.
</div>
