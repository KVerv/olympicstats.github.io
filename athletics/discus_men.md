# Discus Throw men

In this article we will analyse the men's discus throw event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="discus-men-pdf" src="../images/discus/discus-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distributions. We will assume that the data is normal distributed with the sample mean and sample standard deviation. There are 77 fouls registered of the total of 213 throws. This results in a $$ 26.55\% \pm 5.94\% $$ probability of a foul.

We can also look at the cumulative distribution function of the data.
<p><img alt="discus-men-cdf" src="../images/discus/discus-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows a good agreement with a normal distribution. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.64. We must retain the null-hypothesis that the throwing distances are normal distributed with mean $$ 63.92 m \pm 0.36 m $$ and standard deviation 2.61m.

## Medals
Given the distribution of the throwing distances of the athletes we can determine the distribution of the first, second and third distance of a sample. The final consists of 12 athletes each with 3 throws and 8 of them may throw another 3 times. This gives us a sample size of 60 throws. The expected number of fouls is 16 and the expected value of the medal distances with 44 throws are

| Place | Expected Distance (m) | 95% Confidence Interval (m) |
| ----- | ------------- | --------- |
| 1st | 69.66 | [67.58, 72.41] |
| 2nd | 68.61 | [66.98, 70.55] |
| 3nd | 68.01 | [66.57, 69.64] |

The probability that a given distance wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="discus-men-medal" src="../images/discus/discus-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Distance (m) |
|----|-------|
| OR | 69.89|
| WR | 74.35|

We can also look at the probability distributions of the distance of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (m)|  95% Confidence Interval (m) |
| -- | ------ | --- | ---- |
| OR | 90.74% | 70.89 | [69.92, 73.09] |
| WR | 0.68% | 74.94 | [74.36, 76.44] |

<p><img alt="discus-men-record" src="../images/discus/discus-men-records.svg" style="float:center; width:600px" /></p>

## Paris 2024
During the final at the Paris 2024 olympics there were 60 throws registered. Of these throws 19 of them were a foul or $$ 31.67\% \pm 11.78\% $$. This overlaps with the confidence interval of the predicted expected value based on previous olympics, but it is just outside the confidence interval.

Representing Jamaica, Rojé Stona won the gold medal with a distance of 70.00m. This falls well within the 95% confidence interval and deviates only 44cm of the predicted expected value. Furthermore this throw sets a new olympic record. The new record was to be expected from the high probability and the expected value only differs 89cm from the actual value. 

Mykolas Alekna managed to get Silver for Lithuania with a distance of 69.97m. This distance is 1.36m removed from the expected value and falls again well within the confidence interval.

Australia won the bronze medal with Matthew Denny, who threw the discus 69.31m. Again this falls within the confidence interval and differs by 1.30m from the predicted expected value.
