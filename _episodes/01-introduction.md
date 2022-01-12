---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- How to import data set as dataframe?
- How to inspect data frame and access data?
- How to produce an overview of data features?
- How to create data plots using matplotlib?
objectives:
- "To be able to analyse, inspect and visualise the data using Python data frames"
keypoints:
- introduces code to read and inspect the data
- works with a specific data frame and extracts some techniques to get an overview
- discusses the concept 'distribution' as a way of summarising data in a single figure
---
# Challenge: The diabetes data set

Here is a screenshot of the so-called diabetes data set. It is taken from 
[this webpage](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.tab.txt) and it is one of the [example data sets](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html) used to illustrate machine learning functionality in scikit-learn (Part III and Part IV of the course). 


This figure captures only the top part of the data. On the webpage you need to scroll down considerably to view the whole content. Thus, to get an __overview__ of the dataset is the first main task in Data Science. 

The lesson

- introduces code to read and inspect the data
- works with a specific data frame and extracts some techniques to get an overview
- discusses the concept 'distribution' as a way of summarising data in a single figure

To get to know a dataset you need to

- access the data
- check the content
- produce a summary of basic properties

In this lesson we will only look at univariate features where each data column is studied independently of the others. Further properties and bivariate features will be the topic of the next lesson. 



```python

```



# Work Through Example

## Reading data into a Pandas DataFrame

The small practice data file for this section is called 'everleys_data.csv' and can be downloaded using the link given above in "Materials for this Lesson". To start, please create a subfolder called 'data' in the current directory and put the data file in it. It can now be accessed using the relative path 'data/everleys_data.csv' or 'data\everleys_data.csv', respectively.

The file 'everleys_data.csv' contains blood concentrations of calcium and sodium ions from 17 patients with Everley's syndrome. The data are taken from a [BMJ statistics tutorial](https://www.bmj.com/about-bmj/resources-readers/publications/statistics-square-one/7-t-tests). The data are stored as comma-separated values (csv), two values for each patient.

To get to know a dataset, we will use the Pandas package and the Matplotlib plotting. The Pandas package for data science is included in the Anaconda distribution of Python. Check this [link for installation instructions](https://pandas.pydata.org/getting_started.html) to get started. 

If you are not using the Anaconda distribution, pease refer to [these guidelines](https://pandas.pydata.org/docs/getting_started/install.html). 

To use the functions contained in Pandas they need to be imported. Our dataset is in '.csv' format, and we therefore need to read it from a csv file. For this, we import the function `read_csv`. This will create a _Pandas dataframe_.




{% include links.md %}

