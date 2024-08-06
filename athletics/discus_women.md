# Discus Throw Women

In this article we will analyse the women's discus throw event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="discus-women-pdf" src="../images/discus/discus-women-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distributions. We will assume that the data is normal distributed with the sample mean and sample standard deviation. There are 96 fouls registered of the total of 281 throws. This results in a 34.16% probability of a foul.

We can also look at the cumulative distribution function of the data.
<p><img alt="discus-women-cdf" src="../images/discus/discus-women-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the low distances. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.70. We must retain the null-hypothesis that the throwing distances are normal distributed with mean 62.33m and standard deviation 2.51m.

## Medals
Given the distribution of the throwing distances of the athletes we can determine the distribution of the first, second and third distance of a sample. The final consists of 12 athletes each with 3 throws and 8 of them may throw another 3 times. This gives us a sample size of 60 throws. The expected number of fouls is 20 and the expected value of the medal distances with 40 throws are

| Place | Expected Distance (m) |
| ----- | ------------- |
| 1st | 67.75 |
| 2nd | 66.73 |
| 3nd | 66.13 |

The probability that a given distance wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="discus-women-medal" src="../images/discus/discus-women-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Distance (m) |
|----|-------|
| OR | 72.3|
| WR | 76.8|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (m)|
| -- | ------ | --- |
| OR | 1.40% | 72.87 |
| WR | 1.57e-5% | 77.21 |

<p><img alt="discus-women-record" src="../images/discus/discus-women-records.svg" style="float:center; width:600px" /></p>



## Paris 2024