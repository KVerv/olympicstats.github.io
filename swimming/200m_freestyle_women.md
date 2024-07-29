# 200m Freestyle Women

In this article we will analyse the women's 200m freestyle event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="freestyle-200m-women-pdf" src="../images/freestyle/freestyle-200m-women-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data has some structure. It is trimodal and looks like the combination of three normal distributions. The middle distribution however looks to be skewed. Keep in mind that the data only comprises 40 entries. We will ignore this structure for now and assume that the data is normal distributed with the sample mean and sample standard deviation.

We can also look at the cumulative distribution function of the data.
<p><img alt="freestyle-200m-women-cdf" src="../images/freestyle/freestyle-200m-women-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the fast times. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.99. We must retain the null-hypothesis that the finishing times are normal distributed with mean 128.01s and standard deviation 1.97s.

## Medals
Given the distribution of the times of the athletes we can determine the distribution of the first, second and third time of a sample. The final consists of 8 athletes as such we need to consider a samplesize of 8. The expected value of the medal times are

| Place | Expected Time (s) |
| ----- | ------------- |
| 1st | 125.20 |
| 2nd | 126.33 |
| 3nd | 127.08 |

The probability that a given time wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="freestyle-200m-women-medal" src="../images/freestyle/freestyle-200m-women-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Time (s) |
|----|-------|
| OR | 124.1|
| WR | 123.1|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (s)|
| -- | ------ | --- |
| OR | 17.53% | 123.33 |
| WR | 5.03% | 122.45 |

<p><img alt="freestyle-200m-women-record" src="../images/freestyle/freestyle-200m-women-records.svg" style="float:center; width:600px" /></p>



## Paris 2024