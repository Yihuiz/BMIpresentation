---
title       : Slidyfy My Shiny
subtitle    : App BMI caculator
author      : Yihuiz
job         : student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduce the The BMI Calculator

This presentaion will show the code of my application--
the Body Mass Index (BMI) calculator. 

The App can be found at [shinyapps](http://yihuizuo.shinyapps.io/ShinyApp_YihuiZuo)


---
## Creat the User-interface definition 
This shiny App is used to caculate your Body Mass Index (BMI)

The input are :Height  and Weight  

The out put is your BMI

###The calculate equation is 

```r
BMI=weight/(height)^2
```
## also tell you BMI status according to the BMI standard reference



---
## The BMI App interface

![](Graph.JPG) 

---
## Information
Find out more about building applications with Shiny here[My github](https://github.com/Yihuiz/BMIpresentation)




