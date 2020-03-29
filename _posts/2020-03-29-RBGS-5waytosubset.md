---
title:  "5 Ways to Subset a Data Frame in R"
author_profile: false
toc: true
toc_sticky: true
toc_label: "Contents"
categories: 
  - Jekyll
tags:
  - update

---

Often, when you’re working with a large data set, you will only be interested in a small portion of it for your particular analysis. So, how do you sort through all the extraneous variables and observations and extract only those you need? Well, R has several ways of doing this in a process it calls “subsetting.”

The most basic way of subsetting a data frame in R is by using square brackets such that in:

```
 example[x,y] 
```

example is the data frame we want to subset, ‘x’ consists of the rows we want returned, and ‘y’ consists of the columns we want returned. Let’s pull some data from the web and see how this is done on a real data set.

