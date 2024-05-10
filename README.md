# **Probability and Stochastic Processes**
This repository was developed with the aim of meeting the evaluation criteria of the Probability and Stochastic Processes discipline of the Postgraduate Program in Electrical Engineering (PPEE) at the Federal University of Juiz de Fora (UFJF).


## **Principais Comandos Utilizados**

### NumPy
*NumPy is a Python library is an open-source library used mainly for numerical computation. It provides support for multidimensional arrays and matrices, as well as a variety of mathematical functions for working with these data structures.*

### commands

~~~Python
numpy.mean() #Returns the average of the array elements. 
~~~
~~~Python
numpy.median() #Returns the median of the array elements.
~~~
~~~Python
numpy.random() #Implements pseudo-random number generators.
~~~
~~~Python
numpy.std() #Compute the standard deviation along the specified axis.
~~~
~~~Python
numpy.var() #Compute the variance along the specified axis.
~~~
~~~Python
numpy.corrcoef() #Return Pearson product-moment correlation coefficients.
~~~


---
### **SciPy**
*The SciPy library is an open-source library of mathematical tools and algorithms for Python. Its main purpose is to provide functionality for solving mathematical, scientific and engineering problems.*

### commands

The module `scipy.stats()` contains a large number of probability distributions, summary and frequency statistics, correlation functions and statistical tests, masked statistics, kernel density estimation, quasi-Monte Carlo functionality, and more.

~~~Python
scipy.stats.moment() #Calculate the nth moment about the mean for a sample.
~~~
~~~Python
scipy.stats.probplot() #Calculate quantiles for a probability plot, and optionally show the plot.
~~~
~~~Python
scipy.stats.cdf() #Calculate the cumulative distribution function.
~~~
~~~Python
scipy.stats.pdf() #Calculate the probability density function.
~~~
~~~Python
scipy.stats.fit() #Return estimates of shape, location, and scale parameters from data. The default estimation method is Maximum Likelihood Estimation (MLE).
~~~
~~~Python
scipy.stats.interval() #Confidence interval with equal areas around the median.
~~~
~~~Python
scipy.stats.ppf() #Percent point function (inverse of cdf).
~~~
~~~Python
scipy.stats.t.ppf() #Returns the inverse cumulative distribution function of the Student's t distribution.
~~~
~~~Python
scipy.stats.zscore() #Compute the z score of each value in the sample, relative to the sample mean and standard deviation.
~~~
~~~Python
scipy.stats.ttest_ind() #Calculate the T-test for the means of two independent samples of scores.
~~~
~~~Python
scipy.stats.jarque_bera() #Perform the Jarque-Bera goodness of fit test on sample data.
~~~
~~~Python
scipy.stats.chisquare() #Calculate a one-way chi-square test.
~~~
~~~Python
scipy.stats.kstest() #Performs the (one-sample or two-sample) Kolmogorov-Smirnov test for goodness of fit.
~~~
~~~Python
scipy.stats.anderson() #Anderson-Darling test for data coming from a particular distribution.
~~~
~~~Python
scipy.stats.multivariate_normal.fit() #Fit Gaussian mixture model to data
~~~
~~~Python
scipy.optimize.minimize() #Minimization of scalar function of one or more variables.
~~~


---
### **statsmodels**
*statsmodels is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration..*

### commands
~~~Python
statsmodels.stats.diagnostic.lilliefors() #Test assumed normal or exponential distribution using Lilliefors’ test.
~~~
~~~Python
statsmodels.graphics.gofplots.qqplot() #Q-Q plot of the quantiles of x versus the quantiles/ppf of a distribution.
~~~


---
### **pandas**
*pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.*

### commands
~~~Python
pandas.DataFrame.corr() #Compute pairwise correlation of columns, excluding NA/null values.
~~~


---
### **Matplotlib**
*Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.*

### commands

~~~Python
matplotlib.pyplot.hist() #Compute and plot a histogram. 
~~~
~~~Python
matplotlib.pyplot.scatter() #A scatter plot of y vs. x with varying marker size and/or color.
~~~


---
### **seaborn**
*Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.*

### commands

~~~Python
seaborn.ecdfplot() #Plot empirical cumulative distribution functions.
~~~





