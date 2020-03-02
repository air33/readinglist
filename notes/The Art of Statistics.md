# The Art of Statistics

## PPDAC

Problem , Plan, Data, Analysis to Conclusion and communication, and starting again an another cycle

## Odds

the odds for an event is the ratio of the chance of the event happening to the chance of it not happening.

## Mean, median and mode

mode : the most common value

## Pearson correlation coefficient and Spearman's rank correlation

## a good data visualization

1. It contains reliable information

1. The design has benn chosen so that relevant patterns become noticeable

1. It is presented in an attractive manner, but appearance should not get in the way of honesty, clarity and depth

1. When appropriate, it is organized in a way that enables some exploration

## two rules of communication

1. to shut up and listen

1. to know what you want to achieve 
    
    numbers do not speak for themselves

## What's the population

* a little population

* a virual population

* a metaphorical population

## a proper medical trial should ideally obey the following principles

* Controls
    
    a control group who will be given sugar pills or placebos
* Allocation of treatment

    a randomized controlled trial(RCT)
* People should be counted in the groups of which they were allocated

* If possible, people should not even know which group they are in

* Groups should be treated equally

* If possible, those assessing the final outcomes should not know which group the subjects are in

* Measure everyone

* Don't rely on a single study

* Review the evidence systematicaly

## regression to the mean

regression to mediocrity

## residual error

observation = deterministic model + residual error

## All models are wrong, some are useful

## Receiver Operating Characteristic(ROC) curves

sensitivity

    If we are trying to detect surviors, the percentage of true survivors that are correctly predicted is known as the sensitivity of the algorithm

specificity

    the percentage of true non-survivors that are correctly predicted is known as the specificity


By considering all possible thresholds for predicting a survivor, the possible values for the specificity and sensitivity form a curve

## Brier score

mean-squared-error

## Central limit Theorem

the distribution of sample means tends towards the form of a normal distribution with increasing sample size, almost regardless of the shape of the original data distribution

## expected frequency

When faced with the problem of the two coins, you ask yourself, 'What would I expect to happen if I tried the experiemnt a number of times?'

## expectation

The mean of a random variable is also known as its expectation

## standard error

the standard deviation of a statistic is generally termed the standard error

## gambler's fallacy

after a run of heads, and the temptation is to believe that tails is somehow now 'due' so that the proportion gets balanced out - this is known as the gambler's fallacy and is psychological bias

## confidence interval

with repeated application, 95% of such intervals should contain the true value

## null hypothesis

The null hypothesis is what we are willing to assume is the case until proven otherwise

The null hypothesis is never proved or established, but is possibly disproved, in the course of experimentation. Every experiment may be said to exist  only in order to give the facts a chance of disproving the null hypothesis

## P-value

A P-value is the probability of getting a result at least as extrem as we did, if the null hypothesis ( and all other modelling assumptions) wre really true


If an small P-value is observed, then either something very surpring has happened, or the null hypothesis is untrue: the samller the P-value, the more evidence that the null hypothesis might be an inappropriate assumption.

## Statistical significance test

1. Set up a question in terms of a null hypothesis that we waht to check

1. Choose a test statistic that estimates something that , If it turned out to be extreme enough, would lead us to doubt the null hypothesis

1. Generate the sampling distribution of this test statistic , were the null hypothesis true.

1. Check whether our observed statistic lies in the tails of this distribution and summarize this by the P-value. P-value is therefore a particular tail-area

1. Extreme has to be defined carefully

1. Declare the result statistically significant if the P-value is below some critical threshold.

     P < 0.05 and P < 0.01

## t-value

also known as a t-statistic, is the estimate divided by the standard error

## sigmas

a 'two-sigma' result is an observation that is two standard errors away from the null hypothesis


## Type I error and Type II error

a Type I error is made when we reject a null hypothesis when it is true, and a Type II error is made when we do not reject a null hypothesis when in fact the alternative hypothesis holds.

## Odds

The odds of an event is the probability of it happening, divided by the probability of it not happening

## likelihood ratio

The likelihood ratio is the probability of the evidence assume hypothesis A, divided by the probability of the evidence assuming hypothesis B


## Bayes' theorem

the initial odds for a hypothesis X the likelihood ratio = the final odds for the hypothesis

## Prior distribution and Posterior distribution

## multilevel regression and pos-stratification(MRP)

## reproducibility crisis

We do not know what we are not being told

People should not seek to be trusted, since that is granted by others, but to demonstrate the trustworthiness of their work

## ten simple rules for effective statistical practice

1. Statistical methods should enable data to answer scientific questions: Ask 'why am I doing this?', rather than focusing on which particular technique to use

1. Signals always come with noise: It is trying to seperate out the two that makes the subject interesting . Variability is inevitable, and probability models are useful as an abstration

1. Plan ahead, really ahead: This includes the idea of pre-specification in confirmatory experiments - avoiding researcher degress of freedom

1. Worry about data quality: Everything rests on the data.

1. Statistical analysis is more than a set of computations: Do not just plug into formulae or run procedures in software, without knowing why you are doing so

1. Keep it simple: The main communication should be as basic as possible - do not show off skills in complex modelling unless they are really necessary

1. Provide assessments of variability: With the warning that margins of error are generally bigger than claimed

1. Check you assumptions: And make clear when this has not been possible

1. When possible, replicate!: Or encourage others to do so.

1. Make your analysis reproducible: Others should be able to access your data and code

