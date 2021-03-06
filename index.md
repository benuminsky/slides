---
title       : Amazing Widget/Gidget App
subtitle    : Understanding Productivity of Swivel and Sprocket Making
author      : Benjamin Uminsky
job         : (Almost) Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
transition  : rotate
ext_widgets : {rCharts: [libraries/nvd3]}
--- 

## Gidget/Widget

__What if you were able to predict the number of employees you will need to do a particular job?__

_What if you had the insight to know which business processes were under-performing?_

Our Gidget app has been developed for everyone involved in a business setting to observe historical trends and calculate staffing needs based on current swivel and sprocket production/fitting.

As a manager for ACME widgets, you will be able to predict staffing needs based on trends and sophisticated algorithms. Even front line staff will be empowered to see their impact on the performance of processes. The openness of this data will bring to light which operations require a "tune-up" to their process or a "readjustment" to their staffinng levels. 

--- 

## How It Works

The app relies on the following set of R packages:
* dplyr (for data manipulation)
* ggplot2 (for beautiful plotting schemes)
  
  
It uses a dataset that includes information on individual employee performance. The data is then aggregated to show overall trends and patterns, but still uses individual data points to inform the predictive algorithms.

No knowledge of programming or ability to code is necessary in order to use this app. All the data and packages are already loaded onto the app. Datasets are updated on a nightly basis to provide up to date information. The manager simply needs to point and click

---

## How It Works

Start by simply clicking the link below.  

http://benuminsky.shinyapps.io/dataprod/
  
Then choose either the Widget or Gidget bureaus to view data on their specific operations. The primary Gidget operation is "swivel production", which entails employees on an assemply line assembling two smaller pieces to form a swivel.  The core focus of the "sprocket" operation is to fit swivels into pre fabricated sprockets. Those sprockets will then be asssembled in another operation with other parts into the final Gidget product. 

A maanager may select a date range to explore general data patterns using the widget found on the left sidebar panel. You can also enter the number of expected swivels that need to be produced in the "predict staff" widget to estimate the number of staff needed to complete that many swivelswd(. 

---

## Return on Investment

Invest in the right things at the right time. The chart below shows the percentage gained in dollars for the type of business activity investment. The app you saw before represents business intelligence.

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

---
  
## Hard Choices

__What can you do with this real time business intelligence to enhance your operations?__

1. Chuck it out because you don't believe in data analytics

2. Check the app every now and then and see if it jives with your gut instinct as a manager

3. Have your admin assistant review it and tell you what they see.

4. Regularly use the app to make better business decisions.




