# Long Jump Men

In this article we will analyse the men's long jump event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="long-jump-men-pdf" src="../images/discus/long-jump-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distributions, when we only look at the jumps beyond 7m. We will assume that the data is normal distributed with the sample mean and sample standard deviation. There are 85 fouls registered of the total of 202 jumps. This results in a 29.62% probability of a foul.

We can also look at the cumulative distribution function of the data, only considering jumps beyond 7m.
<p><img alt="long-jump-men-cdf" src="../images/discus/long-jump-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the low distances. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.63. We must retain the null-hypothesis that the throwing distances are normal distributed with mean 8.00m and standard deviation 0.20m.

## Medals
Given the distribution of the throwing distances of the athletes we can determine the distribution of the first, second and third distance of a sample. The final consists of 12 athletes each with 3 jumps and 8 of them may jump another 3 times. This gives us a sample size of 60 jumps. The expected number of fouls is 18 and the expected value of the medal distances with 42 jumps are

| Place | Expected Distance (m) |
| ----- | ------------- |
| 1st | 8.43 |
| 2nd | 8.35 |
| 3nd | 8.31 |

The probability that a given distance wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="long-jump-men-medal" src="../images/discus/long-jump-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Distance (m) |
|----|-------|
| OR | 8.90|
| WR | 8.95|

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (m)|
| -- | ------ | --- |
| OR | 0.01% | 8.94 |
| WR | 3.15e-3% | 8.99 |

<p><img alt="long-jump-men-record" src="../images/discus/long-jump-men-records.svg" style="float:center; width:600px" /></p>



## Paris 2024