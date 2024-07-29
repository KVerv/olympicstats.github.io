# 400m Freestyle Men

In this article we will analyse the men's 400m freestyle event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="freestyle-400m-men-pdf" src="../images/freestyle/freestyle-400m-men-distributionpdf.svg" style="float:center; width:300px" /></p>

The distribution of the data has some structure. It is bimodal and looks like the combination of two normal distributions. This structure might represent the two different types of athletes in the final. On one hand we have the athlete that are medal contenders and on the other hand we have the athletes that made it to the final but are not as fast as the medal contenders. Keep in mind that the data only comprises 40 entries. We will ignore this structure for now and assume that the data is normal distributed with the sample mean and sample standard deviation.

We can also look at the cumulative distribution function of the data.
<p><img alt="freestyle-400m-men-cdf" src="../images/freestyle/freestyle-400m-men-distributioncdf.svg" style="float:center; width:300px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the fast times. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.52. We must retain the null-hypothesis that the finishing times are normal distributed with mean 224.74s and standard deviation 2.28s.

## Medals
Given the distribution of the times of the athletes we can determine the distribution of the first, second and third time of a sample. The final consists of 8 athletes as such we need to consider a samplesize of 8. The expected value of the medal times are

| Place | Expected Time (s) |
| ----- | ------------- |
| 1st | 221.50 |
| 2nd | 222.80 |
| 3nd | 223.66 |

The probability that a given time wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="freestyle-400m-men-medal" src="../images/freestyle/freestyle-400m-men-medal.svg" style="float:center; width:300px" /></p>

## Records
The current records are

     | Time (s) |
|----|-------|
| OR | 220.14|
| WR | 220.07|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

     | Probability | Expected Value (s)|
| -- | ------ | --- |
| OR | 16.15% | 219.26 |
| WR | 15.08% | 219.20 |

<p><img alt="freestyle-400m-men-record" src="../images/freestyle/freestyle-400m-men-record.svg" style="float:center; width:300px" /></p>


## Paris 2024
