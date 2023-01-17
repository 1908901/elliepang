---
toc: true
layout: post
description: 
categories: [collegeboard]
title: Program Design and Development Quiz
---

![]({{site.baseurl}}/images/dev.PNG)

## Difficulty

While going through the quiz, I found it difficult to find the differences in each answer choice. All of the answer choices were very similar and it took some time to understand the image of the code.

## Questions 

![]({{site.baseurl}}/images/baa.PNG)

What the direction of the arrows inside the loop represent?

How does numList[k] and numlist[j] represent a number value?

In question 1,why do the end of the brackets overlap each other?


## Takeaways from Question 1

![]({{site.baseurl}}/images/baa.PNG)

The process starts the count at 1. The value of count is displayed inside the loop, after which it is increased by 2 to the following odd number. When count surpasses max, the loop ends, and any positive odd numbers that are less than or equal to max are displayed.

## Takeaways from Question 2

![]({{site.baseurl}}/images/ca.PNG)

The code section begins by adding the x and y numbers, divides the result by x, and then outputs the outcome. A divide-by-zero mistake will occur when result is divided by x if the value of x is 0.

## Takeaways from Question 3

![]({{site.baseurl}}/images/ba.PNG)

The process produces a newList object that is a clone of numList. It is assigned to the element at newList[j] that is at numList[k], and it is allocated to the element at newList[k] that is at newList[j]. As a result, the entries at indices j and k are switched between in newList as opposed to numList. It is crucial to specify that j and k are both between 1 and LENGTH(numList), inclusive, because the process only functions if j and k are valid list indices.

