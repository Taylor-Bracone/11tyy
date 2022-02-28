---
title: Installing open-wc on a MacOS Laptop
description: Set up and equipped installations.
date: 2021-21-09
tags: open source
layout: layouts/post.njk
---

Hi guys! In this post, I am going to talk about how to get dependencies on MacOS and the installation of *open-wc*.

First, make sure you have the correct version of Nodejs installed on your computer. Link: https://nodejs.org/en/. Also, make sure to download Visual Studio Code. Link: https://code.visualstudio.com/download.

Next, create a folder to store projects for IST 402 and name it, for example, “edtechjoker.”

Then, open up the terminal, which can be done multiple ways, but my personal favorite is hold command, space bar, and type in terminal then enter. Next, go to the directory where the folder is stored. For example, cd Desktop (enter) cd *edtechjoker* (enter). Once in that folder from the terminal, a good practice is to ls to see the contents of the folder.

A. Then type the command:
*npm install —global yarn*

If an error states that permissions are needed, then run the command:
*sudo npm install —global yarn*

B. *npm init @open-wc*
 
C. It will prompt you to make a few decisions next:

&nbsp; &nbsp; &nbsp; a. Select *Scaffold* a new project (enter)
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/urd9wm9huioqvrk9yaet.png)

&nbsp; &nbsp; &nbsp; b. Select *Web Component*
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/916fcf7grv8vgt7klp03.png)

&nbsp; &nbsp; &nbsp; c. Use the spacebar to Select *Linting*, *Testing*, *Demoing* (enter)
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fiqqfb8f3fhdvb0m493n.png)

&nbsp; &nbsp; &nbsp; d. Select *No* for Typescript

&nbsp; &nbsp; &nbsp; e. Tag name should be called *hello-world*, all lowercase

&nbsp; &nbsp; &nbsp; f. Select *Yes* to file structure to disk
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vsblngosi1cg00pwyqsk.png)

&nbsp; &nbsp; &nbsp; g. Select *Yes*, with yarn 

D. A confirmation message should pop up
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ta907xgc45ivtn54lmah.png)

**Good Luck!**