Copyright (c) 2020, [Nabeel Khan](https://www.nabeelkhan.com)
All rights reserved.

# Data Science Journey

_**"If You Can't Measure It, You Can't Improve It."**_

A document with bried introduction into [Data Science](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/What%20is%20Data%20Science%20and%20Machine%20Learning.md) and [Machine Learning](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/What%20is%20Data%20Science%20and%20Machine%20Learning.md) with templates to kick-start your projects. This repositry will contain source code to explain the concept into details.

Copyright (c) 2020, [Nabeel Khan](https://www.nabeelkhan.com)
All rights reserved.

## Introduction

Traditional Method --- vs --- Machine Learning Method

![Traditional Method --- vs --- Machine Learning Method](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/images/Traditional%20vs%20Machine%20Learning%20Method.png)

## Approaching Problems as a Data Scientist

I will _sketch_ some portions to keep in mind when structuring your [data science](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/What%20is%20Data%20Science%20and%20Machine%20Learning.md) project before you get into the analysis and modeling phase, then we will get into some technical details regarding preparing data for modeling in the next section. It is very important to ensure you have a well-structured plan for your project beforehand. I cannot emphasize enough on writing down all the details rather just keeping that in your immediate memory.

This document is centered around Jupyter Notebooks because they are a very convenient way to document your planning notes, analysis, and modeling plans, keeping these notes in the same place as your proceeding analysis can help others understand what you're doing when they see your work or provide context for you when you look back at your code after a while.

A large part of [data science](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/What%20is%20Data%20Science%20and%20Machine%20Learning.md) involves the use of [machine learning](https://github.com/nabeelkhan/Data-Science-Journey/blob/main/What%20is%20Data%20Science%20and%20Machine%20Learning.md) to build predictive models. When formulating a plan for predictive modeling, you should start by considering your stakeholder's needs. A perfect model will be useless if it doesn't solve a relevant problem. Planning a strategy around business needs ensures that a successful model will lead to actionable insights.


I will sketch some portions to keep in mind when structuring your data science project before you get into the analysis and modeling phase, then we will get into some technical details regarding preparing data for modeling in the next section. It is very important to ensure you have a well-structured plan for your project beforehand. I cannot emphasize enough on writing down all the details rather just keeping that in your immediate memory.

This document is centered around Jupyter Notebooks because they are a very convenient way to document your planning notes, analysis, and modeling plans, keeping these notes in the same place as your proceeding analysis can help others understand what you're doing when they see your work or provide context for you when you look back at your code after a while.

A large part of data science involves the use of machine learning to build predictive models. When formulating a plan for predictive modeling, you should start by considering your stakeholder's needs. A perfect model will be useless if it doesn't solve a relevant problem. Planning a strategy around business needs ensures that a successful model will lead to actionable insights.

The following are some points to consider when planning your machine learning project:

- What are your business goals?

- What is the type of business problem you are trying to solve?

- How does data science fit into your overall business strategy?

- What is the scope of your project?

- What is the expected outcome of the project?

- What are the assumptions you are making about how to solve the problem?

- What are your constraints?

- What are the steps you will take to solve your problem?

- What types of data do you have to work with?

- How do you plan to prepare your data?

- What types of machine learning models will you use?

- How will you evaluate the performance of your models?

- How will you deploy and communicate your results?

There are a few ways to approach data science problems. I find that it is best to try a few different approaches and choose the one that fits the problem the best. I have listed a few possible strategies below:

The analysis strategy: Design a small model to explore the data and find interesting patterns and relationships.

The predictive strategy: Create a model that makes predictions on new data.

The prescriptive strategy: Identify the optimal actions to take to maximize some value.

The descriptive strategy: Describe the distribution of the data or make visualizations.

The exploratory strategy: Explore the data to make sense of the dataset and determine what questions to ask.

There are several types of machine learning models that can be used to build predictive models. Some of the most common types of models include:

Supervised learning: The model is trained using labeled data, such as training examples with input variables and corresponding output variables. The model learns the mapping from input to output variables.

Unsupervised learning: The model is trained using unlabeled data, such as clustering training examples into groups based on the data.

Semi-supervised learning: The model is trained using a combination of labeled and unlabeled data.

Reinforcement learning: The model learns through feedback from the environment, such as reward functions.

Deep learning: The model uses artificial neural networks, which are inspired by the human brain.

There are also other types of machine learning models that are not related to classification and prediction, such as neural networks that are used for image recognition.

Machine learning models are typically evaluated by comparing the predictions made by the model to the true outcomes. Predictions that are closer to the true outcomes are more likely to be correct. We will discuss some evaluation strategies later in this guide.

The following is an example of how to prepare your data for modeling:

We will create a new directory called data_science_project .

. We will create a new Python Jupyter Notebook called numpy_basics.ipynb .

. We will create a new Python Jupyter Notebook called data_preparation.ipynb .

. We will create a new Python Jupyter Notebook called model_selection.ipynb .

The directory structure should look like this:

data_science_project └── numpy_basics.ipynb

└── data_preparation.ipynb

└── model_selection.ipynb

We will begin by importing numpy and pandas . We will use pandas to clean and prepare our data.

import numpy as np import pandas as pd

We will load the data from a CSV file called wine.csv .

wine = pd . read_csv ( 'data/wine.csv' )

We will use a few pandas methods to clean and prepare our data.

wine = wine . drop ([ 'Name' , 'ClassCode' ], axis = 1 ) wine [ 'ClassCode' ] = wine [ 'ClassCode' ] . astype ( str ) wine . set_index ([ 'Year' , 'ClassCode' ], inplace = True )

We can see that the ClassCode is now a string.

wine . columns . str . class wine . columns . str . dtype

We can see that the Year is an integer.

year = wine . columns . values [ wine . columns . values == 'Year' ] year . shape

We can see that the Year is a 1-d array of integers.

We will have a quick look at the distribution of the number of observations for each class code.

wine . groupby ([ 'ClassCode' , 'Year' ])[ 'Number' ] . mean () . sort_values () . head ()

ClassCode Year 1 1 1992 3 2 1993 4 3 1994 5 4 1995

We can see that there are more entries for class 1 than for class 2.

We will have a quick look at the distribution of the average price for each class code.

wine . groupby ([ 'ClassCode' , 'Year' ])[ 'Price' ] . mean () . sort_values () . head ()

ClassCode Year 0 1 1992 22.0 1 2 1993 24.0 2 3 1994 27.4 3 4 1995 30.5

We can see that there is an increasing trend in average price for each class code.

We will have a quick look at the distribution of the average alcohol level for each class









# Predictive Modeling and Data Analytics
Of the four types of data analytics, predictive modeling is most closely related to the predictive analytics category. The fur types of data analytics are:
- Descriptive Analytics: Descriptive analytics describes the data. For example, a software-as-a-service (SaaS) company sold 2,000 licenses in Q2 and 1,000 licenses in Q1. Descriptive analytics answers the question of how many licenses were sold in Q1 vs. Q2.
- Diagnostic Analytics: Diagnostic analytics is the why behind descriptive analytics. To use the previous example, diagnostic analytics takes data a step further. A data analyst can drill down into quarterly software license sales and determine sales and marketing efforts within each region to reference them against sales growth. They could also see if a sales increase was a result of high-performing salespeople or rising interest within a certain industry.
- Predictive Analytics: Predictive analytics utilizes techniques such as machine learning and data mining to predict what might happen next. It can never predict the future, but it can look at existing data and determine a likely outcome. Data analysts can build predictive models once they have enough data to make predicted outcomes. Predictive analytics differs from data mining because the latter focuses on discovery of the hidden relationships between variables, whereas the former applies a model to determine likely outcomes. A SaaS company could model historical sales data against marketing expenditures across each region to create a prediction model for future revenue based on marketing spend.
- Prescriptive Analytics: Prescriptive analytics takes the final step and offers a recommendation based on a predicted outcome. Once a predictive model is in place, it can recommend actions based on historical data, external data sources, and machine learning algorithms.
