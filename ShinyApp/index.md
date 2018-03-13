---
title       : Finding Anomalies with K-means
subtitle    : With Shiny
author      : Kyle
job         : 
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Anomaly Detection

- At work I anaylize software system data
- Most of it isn't interesting, but occasionally something abnormal happens
- My goal is to find out when that happens and why
- To do this I look for anomalies

<img src="figure/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

--- .class #1

## How to find Anomalies in Data 
- There are a couple ways to find them
1. Density
2. Distance
3. Statistical Properties

Density  | Distance | Statistical
---------| ---------|------------
LOF      | Kmeans   | Parametric Models
CBOF     | Knn      | Mean, Var, Stdev
DENLCUE  | LDOF     | Distribution Assumptions

--- .class #2


## Don't Fear!

- Building some of the models mentioned is difficult
- Luckily R has many models already made
- Kmeans is an example
- Caret also has a ton of built in functions for ML and Anomaly Detection

--- .class #3

## I'll help you get started

- https://kgartrell.shinyapps.io/Finding_Anomalies/
- That link goes to a shiny app that highlights Anomalies using Kmeans

--- .class #4

## Hopefully You Found This Interesting!

- Good luck coming up with your own algorithms


```r
2+2
```

```
## [1] 4
```

### Kindest Regards,
### Kyle

--- .class #5

