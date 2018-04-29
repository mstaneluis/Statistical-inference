# Statistical Inference Course Project

The project consists of two parts:

A simulation exercise.
Basic inferential data analysis.
You will create a report to answer the questions. Given the nature of the series, ideally you'll use knitr to create the reports and convert to a pdf. (I will post a very simple introduction to knitr). However, feel free to use whatever software that you would like to create your pdf.

Each pdf report should be no more than 3 pages with 3 pages of supporting appendix material if needed (code, figures, etcetera).


## Part 1: A simulation exercise
The purpose of this project is to investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. 
The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. 
Set lambda = 0.2 for all of the simulations. This investigates the distribution of averages of 40 exponentials over 1,000 simulations.

## Part 2: Basic Inferential Data Analysis
The purpose of the this data analysis is to analyze the ToothGrowth data set by
comparing the guinea tooth growth by supplement and dose. First, do exploratory data analysis 
on the data set. Then do the comparison with confidence intervals in order to make 
conclusions about the tooth growth.
