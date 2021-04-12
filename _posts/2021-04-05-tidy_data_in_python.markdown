---
layout: post
title:      " Tidy Data in Python"
date:       2021-04-05 11:06:37 -0400
permalink:  tidy_data_in_python
---



Since starting out my data science journey with FlatIron School, I have come to know a few infamous sayings relating to the working life of a data scientist. The most recurring goes something like this:

> "data scientists spend 80% of their time cleaning data and the other 20% complaining about cleaning the data."

Having now completed my first project, I have developed a deeper understanding and appreciation of the time committed to data cleaning, as well as the importance of such a task. 

Producing results is typically not the first step of a data analysis. The vast majority of datasets 'in the wild' will need some amount of inspection and preprocessing. It may even be quite often the case that the entire project will be focused on cleaning the data so that it can be further processed by another data scientist/engineer. 

This post focuses on a small, but important, component of data cleaning: data tidying. Tidy data is a term coined by Hadley Wickham, the creator of many popular R packages, to describe a specific structure of data that makes for easy analysis. 

*The full Tidy Data paper can be found [here](https://vita.had.co.nz/papers/tidy-data.pdf) for a complete understanding.*



## Defining tidy data

Tidy data is a specific structure of data that makes analysis easier. A tidy dataset meets the following 3 conditions:

1. Each variable forms a column
2. Each observation forms a row
3. Each type of observational unit forms a table

Any dataset that does not meet this definition is considered 'messy'. 


## Tidying a messy dataset

Messy data can appear deceptively clean and tidy, especially when being exposed to it for the first time. 
Let's take a look at some data on the average arrival delay for different airlines flying out of different cities and see how this can be transformed into a tidy structure. 



Although the above appears perfectly readable, it is not technically in the tidy data structure. The main issue with this dataset is that some of the column names are variable values themselves. 
*A variable can be defined as "anythig that is not consistent or having a fixed pattern; liable to change."*

The variables can be inferred from the description of the problem and are identified as:
1. airline
2. origin airport
3. average arrival delay 

In line with the definition of a tidy dataset, each variable needs to form its own column. 

To tidy this dataset, it will need to be restructured so that each of the variables identified a


<img src="https://raw.githubusercontent.com/ramandiprai/Blogging/main/data_1.png" width="300" >





