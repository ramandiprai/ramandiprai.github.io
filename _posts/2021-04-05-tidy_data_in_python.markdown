---
layout: post
title:      " Tidy Data in Python"
date:       2021-04-05 15:06:36 +0000
permalink:  tidy_data_in_python
---



Since starting out my data science journey with FlatIron School, I have come to know many infamous sayings relating to the working life of a data scientist. The most recurring goes something like this:

> "data scientists spend 80% of their time cleaning data and the other 20% complaining about cleaning the data."

Having now completed my first project, I have developed a deeper understanding and appreciation of the time committed to data cleaning, as well as the importance of such a task. 

Producing results is typically not the first step of a data analysis. The vast majority of datasets 'in the wild' will need some amount of inspection and preprocessing. It may even be quite often the case that the entire project will be focused on cleaning the data so that it can be further processed by another data scientist/engineer. 

This post focuses on a small, but important, component of data cleaning: data tidying. Tidy data is a term coined by Hadley Wickham, the creator of many popular R packages, to describe a specific structure of data that makes for easy analysis. 

*The complete Tidy Data paper can be found [here](https://vita.had.co.nz/papers/tidy-data.pdf) for a complete understanding.*



#### Defining tidy data

Tidy data is a specific structure of data that makes analysis easier. A tidy dataset meets the following 3 conditions:

1. Each variable forms a column
2. Each observation forms a row
3. Each type of observational unit forms a table

Any dataset that does not meet this definition is considered 'messy'. 


#### Tidying a messy dataset

Messy data can appear deceptively clean and tidy, especially when being exposed to it for the first time. 
```
import pandas as pd
arrival_delay = pd.read_csv('../data/tidy/aver
```

![Imgur](https://imgur.com/mhX8ue9)







