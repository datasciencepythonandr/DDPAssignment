---
title: "Reproducible Pitch Presentation"
output: 
  ioslides_presentation: 
    keep_md: yes
date: '5-Jan-2021'
---




## Use of Application
* To demonstrates how a distribution of randomly generated numbers approximate normal distribution when number of observations gets large
* Slider is used in place of input as per below code

```r
input = 50
dist <- rnorm(input)
        hist(dist)
```

<img src="index_files/figure-html/unnamed-chunk-1-1.png" style="display: block; margin: auto;" />

```


## User Interface

![User Interface](./1.png)



## Small Observations

![Small Observations](./2.png)


## Large Observations (Normal Distribution Approximation)

![Large Observations](./3.png)
