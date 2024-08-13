# Long Jump Men

In this article we will analyse the men's long jump event at the olympics. For this we will use the data from the finals of all previous summer olympics from Athens 2004 up to Tokio 2020. 

## The distribution

<p><img alt="long-jump-men-pdf" src="../images/long-jump/long-jump-men-distributionpdf.svg" style="float:center; width:600px" /></p>

The distribution of the data looks like a normal distributions, when we only look at the jumps beyond 7m. We will assume that the data is normal distributed with the sample mean and sample standard deviation. There are 85 fouls registered of the total of 202 jumps. This results in a $$ 29.62\% \pm 6.30\% $$ probability of a foul.

We can also look at the cumulative distribution function of the data, only considering jumps beyond 7m.
<p><img alt="long-jump-men-cdf" src="../images/long-jump/long-jump-men-distributioncdf.svg" style="float:center; width:600px" /></p>
This plot also shows some deviations from the fitted distribution but it doesn't look that bad especially for the low distances. We can perform the Anderson-Darling test to check if the data is explained by the fitted distribution. The p-value of an one-sample Anderson-Darlign test is given by 0.63. We must retain the null-hypothesis that the throwing distances are normal distributed with mean 8.00m and standard deviation 0.20m.

## Medals
Given the distribution of the throwing distances of the athletes we can determine the distribution of the first, second and third distance of a sample. The final consists of 12 athletes each with 3 jumps and 8 of them may jump another 3 times. This gives us a sample size of 60 jumps. The expected number of fouls is 18 and the expected value of the medal distances with 42 jumps are

| Place | Expected Distance (m) | 95% Confidence Interval (m) |
| ----- | ------------- | --------- |
| 1st | 8.43 | [8.27, 8.65] |
| 2nd | 8.35 | [8.22, 8.51] |
| 3nd | 8.31 | [8.19, 8.44] |

The probability that a given distance wins at least a gold, silver or bronze medal can also be calculated.
<p><img alt="long-jump-men-medal" src="../images/long-jump/long-jump-men-medal.svg" style="float:center; width:600px" /></p>

## Records
The current records are

| Record | Distance (m) |
|----|------- |
| OR | 8.90 |
| WR | 8.95 |

We can also look at the probability distributions of the time of the new record. This also allows for the calculation of the expected value of the new records and the probability that we'll see a new record.

| Record | Probability | Expected Value (m)|  95% Confidence Interval (m) |
| -- | ------ | --- | ---- |
| OR | 0.051% | 8.94 | [8.90, 9.05] |
| WR | 0.015% | 8.99 | [8.95, 9.09] |

<p><img alt="long-jump-men-record" src="../images/long-jump/long-jump-men-records.svg" style="float:center; width:600px" /></p>

## Paris 2024
During the final at the Paris 2024 olympics there were 59 jumps registered. Of these jumps 15 of them were a foul or 25.42% $\pm$ 11.11%. This overlaps with the confidence interval of the predicted expected value based on previous olympics.

The greek Miltiadis Tentoglou won the gold medal with a distance of 8.48m. This falls well within the 95% confidence interval and deviates only 5cm of the predicted expected value.

Wayne Pinnock managed to get Silver for Jamaica with a distance of 8.36m. This distance is only 1cm removed from the expected value and falls again well within the confidence interval.

Italy won the bronze medal with Mattia Furlani, who jumped 8.34m. Again this falls well within the confidence interval and only differs by 3cm from the predicted expected value.

At the Paris 2024 olympics no records were broken in the men's long jump discipline. This was to be expected if one looks at the small probabilities to break this records.
