---
title: "RMark"
output: pdf_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

Provides functions for unit conversions. This package includes functions to convert  
          fahrenheit to celsius, miles to kilometers, miles to feet and kg to lb.
          
          
> fah_to_cel <- function(ftemp){
+   ctemp <- (ftemp - 32) * 5 / 9
+   return(ctemp)
+ }
> 
> 
> mi_to_km <- function(mi){
+   km <- mi / 0.62137
+   return(km)
+ }

## Including Plots

This package includes the following functions:

> fah_to_cel(36)
[1] 2.222222
> mi_to_km(23)
[1] 37.01498

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
