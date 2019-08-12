---
layout: default
title: Course Notes
---

<style>
ul {
font-family: "Century Gothic", CenturyGothic, AppleGothic, sans-serif; 
  font-size: 16px; 
  font-style: normal; 
  font-variant: small-caps; 
  font-weight: 100;
  line-height: 26.4px;
}
h2 { 
  font-size: 22px;  
  color: maroon;
}
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
 </style>
 

<br>


# Getting Started

<iframe src="https://player.vimeo.com/video/180644880" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
<p><a href="https://vimeo.com/180644880">R in 60 Seconds</a> from <a href="https://vimeo.com/user28525110">DS4PS</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

* What is R?
* Tour of R Studio
* Packages 
* Navigation (working directories, list objects, create folders)
* [Markdown](https://ds4ps.org/cpp-526-fall-2019/markdown/)
* [Data-Driven Documents](https://ds4ps.org/docs/) 
* Style Guides 
 
## CH 01 - R as a Calculator
* Assignment 
* Mathematical Operators 
 
## [CH 02 - Functions](http://ds4ps.org/datacamp-light-demo-for-rmd/calc-mortgage.html) 
* Input-Output Devices 
* Object-Oriented Coding 
* Arguments 
* Values 
* Returns 
* Reading Help Files 

# One-Dimensional Datasets

## CH 03 - Vectors
* Observations vs Variables (rows vs columns) 
* Vector Types
  - Numeric
  - Character
  - Factors (ordered vs unordered) 
  - Logical (true/false) 
* Checking Vector Types

## CH 04 - Working with Vectors
* Built-In Vectors: e.g. LETTERS
* Generating Vectors
* Missing Values and Non-Numbers
* Empty vectors: NULL


## CH 04 - Altering Vectors
* Defining factors, relevel()
* Recoding Values 
* Find and replace
* Variable Transformations
  - Vectorized addition
  - Defining new vector as function of others:  ifelse(), gsub(), [] <- 
* Casting 
* Implicit Casting (coercion)


## CH 05 –Identifying Groups within Data 
* Set theory as categories and membership 
* Logical Operators 
  - equal
  - not equal 
  - greater than or less than 
  - opposite of
* Compound Statements:  AND and OR
* Casting logical vectors 
* Algebra with logical vectors 
* Defining groups 
  - from categorical variables
  - from numeric variables
  - missing values as a group
