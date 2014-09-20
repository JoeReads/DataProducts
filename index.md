---
title       : The FTE Calculator
subtitle    : Budget Prep Tools - Dialogue Services, Inc
author      : Joe
job         : Budget Director
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Why you need to use the FTE Calculator

1. At Dialogue Services we provide all the tools you need to do your job in the most efficient way.


2. When you are preparing your departmental budget you will need to enter the total hours for all your staff members using form 56 and entering your total number of FTEs on line 22.


3. The FTE Calculator makes it easy to convert the total number of staff hours in your departmental budget to FTEs.


--- .class #id 

## Calculating FTEs using alternate methods

1. If you have R available you could do something like this:


```r
t<-sum(230,456,3000,5000,1900,457)
Fte<- t/2080
print(Fte)
```

```
## [1] 5.309
```

2. If you have a desk calculator you could enter the numbers, find the total and then divide

3. Using the FTE calculator you simply enter the total, press submit and the FTE calculation is available for entry on the form.

(An update of FTE Calculator is in the final stages of testing. The next version to be released in the Fall will allow entry of individual hours as well as total hours)



--- &radio

## Should I use the FTE Calculator?

Quiz

### I would use the FTE Calculator If the Total number of staff hours in my department is:

1. _234 hours_

2. _3000 hours_

3. 0 hours

4. _9000 hours_

5. _1 or more hours_

*** .hint 

If your budget is more than 0 hours you will have a total number of hours to enter.

*** .explanation 

If your department is not staffed with volunteers you will have a number greater than 0 to enter for total hours and therefore you should use the FTE calculator.



---

## Accessing the FTE Calculator

#### To use the FTE Calculator

1. go to https://joereads.shinyapps.io/App-1/

2. Find the planned work hours for each of your staff members for the coming year

3. Find the total hours for all staff members including yourself

4. Enter the total into the FTE Calculator

5. Press submit

6. Enter the number of FTEs on your budget form


---
