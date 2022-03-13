---
title: 'Fatal problem of using the public opinion polls or questionnaires'
date: 2022-03-09 11:20:20
permalink: /posts/2022/03/CLT-Bernoulli-short-1/
excerpt_separator: <!--more-->'
toc: true
tags:
  - Central limit theorem
  - Probability distribuiton simulator
  - Bernoulli distribution
---

> Fatal errors pierce into results of the opinion polls while set p = 0.5 and use the property of thecentral limit theorem since (1) the approximating continuous distribution does not mean the "real" continuous distribution, (2) the minimal sample size of the central limit theorem does not be tested, but the theorem is applied, and (3) there is no test for the probability under the specific p and sample size. 

> This post shows the evidecne at the case of p = 0.5. Mail me to obtain more evidence of other p.
> Seek the coorperation to write papers. [Mailing me](mailto:mylee0989@gmail.com).

Click the title to read more.

<!--more-->'

A population proportion test for opinion polls or questionnaires is based on Bernoulli distribution. Assuming that each random sample is independently and randomly drawing from Bernoulli distribution, the sum of random samples follows Binomial distribution and the central limit theorem guarantees that the sum of random samples approximates to Normal distribution.

Interval estimation is set to p = 0.5 to calculate the standard deviation because the population proportion is unknown and there is not enough information for p. Therefore, I excerpted the outcomes of setting p=0.5 from the complete results to show the problem of using the central limit theorem, that the Z distribution can be used if the sample size exceeds 30.

In addition, gif below also shows the minimal sample size required for the central limit theorem under diffrernt population proportion. Finally, gif exhibits a probability value of p = 0.5 under the critical value of maintaining the Z distribution for different sample sizes.

![](https://raw.githubusercontent.com/meiyulee/pic001/master/beroulli_distribution_polls.gif)