# 200m butterfly men

In this article we will analyse the men's 200m butterfly event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="butterfly-200m-men-pdf" src="../images/butterfly/butterfly-200m-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distribution. Keep in mind that the data only comprises 40 entries. We will assume that the data is normal distributed with the sample mean and sample standard deviation.

We can also look at the cumulative distribution function of the data.
<p><img alt="butterfly-200m-men-cdf" src="../images/butterfly/butterfly-200m-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the fast times. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.99. We must retain the null-hypothesis that the finishing times are normal distributed with mean 114.64s and standard deviation 1.37s.

## Medals
Given the distribution of the times of the athletes we can determine the distribution of the first, second and third time of a sample. The final consists of 8 athletes as such we need to consider a samplesize of 8. The expected value of the medal times are

| Place | Expected Time (s) |
| ----- | ------------- |
| 1st | 112.69 |
| 2nd | 113.47 |
| 3nd | 113.99 |

The probability that a given time wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="butterfly-200m-men-medal" src="../images/butterfly/butterfly-200m-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Time (s) |
|----|-------|
| OR | 111.25|
| WR | 110.34|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (s)|
| -- | ------ | --- |
| OR | 5.26% | 110.80 |
| WR | 0.68% | 109.97 |

<p><img alt="butterfly-200m-men-record" src="../images/butterfly/butterfly-200m-men-records.svg" style="float:center; width:600px" /></p>



## Paris 2024
