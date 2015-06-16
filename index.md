---
coursetitle: Introduction to C Programming
layout: page
title: Introduction
---
The best way to learn how to program is to do something useful,
so this introduction to C is built around a common scientific task:
data analysis.

Our real goal isn't to teach you C,
but to teach you the basic concepts that all programming depends on.
We use C in our lessons because:

1.  we have to use *something* for examples;
2.  it's free, well-documented, and runs almost everywhere;

But the two most important things are
to use whatever language your colleagues are using,
so that you can share your work with them easily,
and to use that language *well*.

We are studying inflammation in patients who have been given a new treatment for arthritis,
and need to analyze the first dozen data sets of their daily inflammation.
The data sets are stored in [comma-separated values](reference.html#comma-separated-values) (CSV) format:
each row holds information for a single patient,
and the columns represent successive days.
The first few rows of our first file look like this:

~~~
0,0,1,3,1,2,4,7,8,3,3,3,10,5,7,4,7,7,12,18,6,13,11,11,7,7,4,6,8,8,4,4,5,7,3,4,2,3,0,0
0,1,2,1,2,1,3,2,2,6,10,11,5,9,4,4,7,16,8,6,18,4,12,5,12,7,11,5,11,3,3,5,4,4,5,5,1,1,0,1
0,1,1,3,3,2,6,2,5,9,5,7,4,5,4,15,5,11,9,10,19,14,12,17,7,12,11,7,4,2,10,5,4,2,2,3,2,2,1,1
0,0,2,0,4,2,2,1,6,7,10,7,9,13,8,8,15,10,10,7,17,4,4,7,6,15,6,4,9,11,3,5,6,3,3,4,2,3,2,1
0,1,1,3,3,1,3,5,2,4,4,7,6,5,3,10,8,10,6,17,9,14,9,7,13,9,12,6,7,7,9,6,3,2,2,4,2,0,1,1
~~~

We want to:

*   load that data into memory,
*   calculate the average inflammation per day across all patients, and
*   plot the result.

To do all that, we'll have to learn a little bit about programming.

> ## Prerequisites {.prereq}
>
> Learners need to understand the concepts of files and directories
> (including the working directory) and how to start a shell.
> This lesson references Gnu gcc compiler.


> ## Getting ready {.getready}
>
> You need to download some files to follow this lesson:
>
> 1. Make a new folder in your Desktop called `cintro`.
> 2. Download [introc.exe](introc.exe) and move the file to this folder.
> 3. If it's not unzipped yet, double-click on it to unzip it. You should end up with a new folder called `data`.
> 4. You can access this folder from the Unix shell with:
>
> ~~~ {.input}
> $ cd && cd Desktop/introc/
> ~~~

## Topics

1.  [Topic Title One](01-one.html)
2.  [Topic Title Two](02-two.html)

## Other Resources
 
*   [Reference](reference.html)
*   [Discussion](discussion.html)
