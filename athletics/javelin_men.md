# Javelin Throw Men

In this article we will analyse the men's javelin throw event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="javelin-men-pdf" src="../images/javelin/javelin-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distributions. We will assume that the data is normal distributed with the sample mean and sample standard deviation. There are 77 fouls registered of the total of 209 throws. This results in a $$ 26.92\% \pm 6.02\% $$ probability of a foul.

We can also look at the cumulative distribution function of the data.
<p><img alt="javelin-men-cdf" src="../images/javelin/javelin-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows a good agreement with a normal distribution. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.96. We must retain the null-hypothesis that the throwing distances are normal distributed with mean $$ 81.08 m \pm 0.45 m $$ and standard deviation 3.23m.

## Medals
Given the distribution of the throwing distances of the athletes we can determine the distribution of the first, second and third distance of a sample. The final consists of 12 athletes each with 3 throws and 8 of them may throw another 3 times. This gives us a sample size of 60 throws. The expected number of fouls is 17 and the expected value of the medal distances with 43 throws are

| Place | Expected Distance (m) | 95% Confidence Interval (m) |
| ----- | ------------- | --------- |
| 1st | 88.16 | [85.57, 91.58] |
| 2nd | 86.86 | [84.83, 89.27] |
| 3nd | 86.11 | [84.32, 88.14] |

The probability that a given distance wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="javelin-men-medal" src="../images/javelin/javelin-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Distance (m) |
|----|-------|
| OR | 90.57|
| WR | 98.48|

We can also look at the probability distributions of the distance of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (m)|  95% Confidence Interval (m) |
| -- | ------ | --- | ---- |
| OR | 29.51% | 91.52 | [90.59, 93.83] |
| WR | 7.73e-4% | 99.04 | [98.49, 1000.52] |

<p><img alt="javelin-men-record" src="../images/javelin/javelin-men-records.svg" style="float:center; width:600px" /></p>

## Paris 2024
During the final at the Paris 2024 olympics there were 59 throws registered. Of these throws 15 of them were a foul or $$ 25.42\% \pm 11.12\% $$. This agrees well with the predicted expected value based on previous olympics.

Representing Pakistan, Arshad Nadeem won the gold medal with a distance of 92.97m. This falls slightly out of the 95% confidence interval and deviates 4.81m of the predicted expected value. Furthermore this throw sets a new olympic record. The new record was to be expected from the high probability and the expected value only differs 1.45m from the actual value. This value falls well within the predicted confidence interval.

Neeraj Chopra managed to get Silver for India with a distance of 89.45m. This distance is 2.59m removed from the expected value and falls slightly out of the confidence interval.

Grenada won the bronze medal with Anderson Peters, who threw the javelin 88.45m. Again this falls slightly out of the confidence interval and differs by 2.34m from the predicted expected value.