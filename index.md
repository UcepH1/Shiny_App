---
title       : Car Performance Shiny App
subtitle    : 
author      : UcepH1
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction 

The aim of this pitch is to present the *Car Performance* Shiny App submitted for the last assignment for the *Developping Data Products* course.

The App uses *Motor Trend Car Road Tests Data* to show car perfomance based on user's choice of minimum horse power.

--- .class #id 

## Ui.R

The ***Ui.R*** file contains the structure and the aesthetic caracteristics of the App.

A brief documentation comes with the App to help user start using it : 

The slider allows the user to select the minimum horse power desired.

---

## Server.R

The ***Server.R*** file contains the calculations of the App.

The server loads the data set and performs subsetting and plotting operations to produce the plot showing cars which horse power is at least equal to the value set by user.

The following plot was produced using a threshold horsepower of ***100*** :

![plot of chunk mtcars](assets/fig/mtcars-1.png)


---

## Conclusion


In this project, we deployed a Shiny App that renders car caracteristics according to a specific horse power threshold set by user.





