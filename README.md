# Statistic For Data Science
Statistical data science is at the core of modern data analytics that turn data into intelligence to inform decision-making and solve challenging problems.

## Type of Variable
 * Quantitative
   * Continuous
   * Discrete
 * Qualitative
   * Ordinal
   * Nominal
## Probability
Probability means possibility. It is a branch of mathematics that deals with the occurrence of a random event.
## Measure of Central Tendency
  * Mean = Average value
  * Median = middle value
  * Mode = Value that occurs most often
## Range
Calculate the difference by subtracting the smallest from the largest
## Variance
The variance is a measure of variability. It is calculated by taking the average of squared deviations from the mean. Variance tells you the degree of spread in your data set. The more spread the data, the larger the variance is in relation to the mean
## Standard Deviation
A standard deviation (or σ) is a measure of how dispersed the data is in relation to the mean. Low standard deviation means data are clustered around the mean, and high standard deviation indicates data are more spread out.
## Quantile
A quantile defines a particular part of a data set, i.e. a quantile determines how many values in a distribution are above or below a certain limit.
Q0 is the smallest value in the data.

Q1 is the value separating the first quarter from the second quarter of the data.

Q2 is the middle value (median), separating the bottom from the top half.

Q3 is the value separating the third quarter from the fourth quarter

Q4 is the largest value in the data

## Skewness
Skewness is a measure of the asymmetry of a distribution. A distribution is asymmetrical when its left and right side are not mirror images. A distribution can have right (or positive), left (or negative), or no skewness.
## Distribution
 * No skew
 * Right Skew
 * Left Skew
## Correlation
Correlation is a statistical measure that expresses the extent to which two variables are linearly related 

## Outlier and Anomaly 
An outlier is an observation that lies an abnormal distance from other values in a random sample from a population.

An unexpected change within these data patterns, or an event that does not conform to the expected data pattern, is considered an anomaly.
Using IQR

IQR tells how spread the middle values are. it can be used to tell when a value is to far from the middle

An outlier is a point which fall more than 1.5 times interquartile range above third quartile or below first quartile

We will use the same dataset

Step 1 :

Arrange the data in increasing order

Calculate first (Q1) and third quartile (Q3)

Find lower bound Q1 * 1.5

Find upper bound Q3 * 1.5

Anything that lies outside of lower and upper bound is outlier
## Handling Outlier
Because outlier have a large influence on statistics derived from the dataset it usually removed if the data used for machine learning and other stuff.

to do that we can select data that in the range between lower bound and upper bound of data.
## Handling Missing Value
The handling of missing data is very important during the preprocessing of the dataset as many machine learning algorithms do not support missing values.

the handling of this missing values is diffrent based on numerical or categorocal values of the data.
  * Numeric with median of data
  * Categorical with mode of data
## Inferential Statistic - Confidence Interval
Hypothesis testing is a form of statistical inference that uses data from a sample to draw conclusions about a population parameter or a population probability distribution.
## Inferential Statistic - Hypothesis Testing

Paired sample t-test :

The paired sample t-test is also called dependent sample t-test. It's an uni variate test that tests for significant difference beetween e related variable. An example of this is if you where to collect the blood pressure for an individual before and after some treatment, condition, or time point.

H0 :

means defference between two sample is 0

H1 : mean defference two sample is not 0
