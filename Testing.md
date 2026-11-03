---
title: "Testing"
author: "Gavyn Jensen-Schneider"
date: "11-03-2026"
output:
  html_document:
    keep_md: true
---



``` r
datanorm <- rnorm(100, 24, 6)
plot(datanorm)
```

![](Testing_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

``` r
summary(datanorm)
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##   10.38   20.64   23.75   23.78   27.30   40.90
```
