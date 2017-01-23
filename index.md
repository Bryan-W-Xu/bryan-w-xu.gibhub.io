---
title       : Shiny App to Predict Son's Height
subtitle    : DDP Wk4 Project - Part 2
author      : Bryan Xu
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
url:
  assets: ./assets
---

## Goal

Predict son's height based on father's height


--- &twocol

## Model

*** =left

> A linear model built with the father.son dataset

- library(UsingR)
- data("father.son")

> lm(sheight ~ fheight, data = father.son)

*** =right

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)


--- 

## How to input father's height

- Click and Slide the horizontal bar at the bottom of the page.
- A numeric value shows above the cursor. 
- Father's height changes in steps of 0.25 inches.
- Releasing the mouse will select an input value.




![alt text](inputbar.png)


--- &twocol
*** =right

## Prediction of Son's Height


- Predicted son's height will show in bold red number about the input bar.
- a big red dot will be plotted in the graph.

*** =left
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)
![alt text](inputbar2.png)




