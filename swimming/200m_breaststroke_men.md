# 200m breaststroke men

In this article we will analyse the men's 200m breaststroke event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="breaststroke-200m-men-pdf" src="../images/breaststroke/breaststroke-200m-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distribution. Keep in mind that the data only comprises 40 entries. We will assume that the data is normal distributed with the sample mean and sample standard deviation.

We can also look at the cumulative distribution function of the data.
<p><img alt="breaststroke-200m-men-cdf" src="../images/breaststroke/breaststroke-200m-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the fast times. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.36. We must retain the null-hypothesis that the finishing times are normal distributed with mean 128.86s and standard deviation 1.50s.

## Medals
Given the distribution of the times of the athletes we can determine the distribution of the first, second and third time of a sample. The final consists of 8 athletes as such we need to consider a samplesize of 8. The expected value of the medal times are

| Place | Expected Time (s) |
| ----- | ------------- |
| 1st | 126.73 |
| 2nd | 127.58 |
| 3nd | 128.15 |

The probability that a given time wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="breaststroke-200m-men-medal" src="../images/breaststroke/breaststroke-200m-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Time (s) |
|----|-------|
| OR | 126.38|
| WR | 125.48|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (s)|
| -- | ------ | --- |
| OR | 33.05% | 125.70 |
| WR | 9.22% | 124.95 |

<p><img alt="breaststroke-200m-men-record" src="../images/breaststroke/breaststroke-200m-men-records.svg" style="float:center; width:600px" /></p>



## Paris 2024
