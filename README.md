# MLS-Tasks-2020
Repository for Machine Learning &amp; Statistics Module for Assessment Tasks 2020

## Running the Jupyter Notebook
1. Click this [link](https://github.com/Dowline1/MLS-Tasks-2020) for my Github repository.
2. Click the download button to save a copy of the repository on your machine.
3. Make sure you have Python installed including Jupyter, if you require installation please follow instructions in this [link](https://www.anaconda.com/distribution/) to download Python via Anaconda.
4. Use your command line such as CMDER to navigate to the folder housing the Git repository, download for CMDER found via this [link](https://cmder.net/).
5. Once in the folder type the command "Jupyter Notebook" and click enter.
6. This will open a Jupyter Notebook in your default web browser, click on the file "MLS-Tasks-2020.ipynb".
7. Once in the Jupyter Notebook itself click on Kernel then Restart And Run All as per **image below**, this will run the code and generate all graphs.

<img  src="Resources/Jupyter_Instructions.png">

All references, data and commentary relating to project can be found within the Jupyter Notebook, please refer here for my submission.

## Introduction
### Square Root of 2
Most of the calculations that we are used to using in mathematics have an opposite or inverse to the calculation, for example subtraction is the opposite of addition division is the opposite to multiplication and so on. The same can be said for powers or exponents of numbers with the inverse of exponents being square roots  (Math.com, n.d.).

Simply explained the square root of a number n is the number that when multiplied by itself is equal to n some of which are perfect squares and do not require any decimal places. The √100 is equal to 10 as 10 x 10 or 10 to the power of 2 equals 100 and is a perfect square, whereas the √30 is equal to roughly 5.4772 and so it not a perfect square as it's square root is not a whole number.

Within my jupyter notebook I will be writing a function that calculates √2 to 100 decimal places without using any python modules i.e. no imports will be used to create my function or achieve the desired result, please refer to Question 1 in the notebook for further details and for function.

###  Chi-squared test
The Chi Square Test has two distinct types which both use the chi-square statistic and distribution in there calculation (Glen, 2020). 

The first is a chi-square goodness of fit test and is used to determine if a sample of data matches up with the population. The second is a chi-square test for independence which compares two variables or categories using a contingency table in order to determine if the categories are related.

For this aspect of the Tasks Assignment the goal is to verify that the chi-square value of the example used in (Wikipedia Contributors, 2020) relating to a neighborhood and the distribution of the residents working class equates to 24.6 using scipy.stats. Please refer to question 2 section within the notebook to see my solution for verification of the Wikipedia page results.

### Standard Deviation
The Standard Deviation is a measure of how far apart numbers are in a dataset denoted by the symbol σ or sigma. Standard Deviation is calculated by taking the square root of the **variance** with variance being calculated by taking each value in the set, subtracting this from the overall average as the **difference** and finally squaring this difference and finding the average of all these differences giving you the variance (Math is Fun, 2017).

In my notebook in section labeled question 3 I complete an analysis to compare and contrast the Sample and Population Standard Deviation calculations, I also conduct a simulation of a population of known Standard Deviation by which I compare the output of each method of calculation.

### Iris Dataset
The Iris dataset is a famous multi-variant dataset created by Ronald Fisher for his 1936 publication on the use of multiple measurements in linear discriminant analysis. For the dataset Fisher took length and width measurements of Sepals and Petals of 150 plants evenly over 3 species of Iris Flower. 

The dataset is commonly used in the teaching of machine learning techniques and in this project we will attempt to use <i>k</i>-Means Clustering to identify species of iris after training the model. You can find all of my workings for my <i>k</i>-Means Cluster in section labeled question 4 whereby I train my model with different parameters and explain how predictions can be made using these models.