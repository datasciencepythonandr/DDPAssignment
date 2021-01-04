---
title: "Course Project: Shiny Application and Reproducible Pitch"
output: 
  html_document:
    keep_md: true 
---




## Background

This peer assessed assignment has two parts. First, you will create a Shiny application and deploy it on Rstudio's servers. Second, you will use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about your application.

Your Shiny Application

Write a shiny application with associated supporting documentation. The documentation should be thought of as whatever a user will need to get started using your application.
Deploy the application on Rstudio's shiny server
Share the application link by pasting it into the provided text box
Share your server.R and ui.R code on github
The application must include the following:

* Some form of input (widget: textbox, radio button, checkbox, ...)
* Some operation on the ui input in sever.R
* Some reactive output displayed as a result of server calculations
* You must also include enough documentation so that a novice user could use your application.
* The documentation should be at the Shiny website itself. Do not post to an external link.


## Shiny Application

This shiny application demonstrates how a distribution of randomly generated numbers approximate normal distribution when number of observations gets large. The slider will control the number of observation generated. User can observe the approximation towards normal as the slider goes from left to right.

## Files in Repository

* ui.R
* server.R
* README.md


