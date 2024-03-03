+++
authors = ["Dr.BlueBird"]
title = "Sensitivity and Specificity"
date = "2024-01-10"
math = true
tags = [
    "sensitivity",
    "specificity",
]
categories = [
    "Biostats",
]
+++


## Sensitivity (True positive)

= Positive among all true

Sensitivity is for describing how sensitive a classifier or test is. Given a "true", the probability of spotting this "true" is called sensitivity.
$$
\text{Sensitivity}=P(\text{positive}|\text{true})
$$
For example, a blood screening is used for spotting a disease. **Sensitivity of the blood screening means the probability of getting a positive result when that person is actually sick**.  A very sensitive blood test will spot almost all sick people and even take healthy people as sick (low specificity).

## Specificity (True negative)

= negative among all false

Specificity is less straightforward to interpret. It is for describing how specific a classifier is. High specificity usually means a test or classifier is tolerant.

**If a classifier is very specific, it means this classifier is giving negative result blindly**. It only gives positive result when the objective satisfies **very SPECIFIC** conditions. 

A super specific clinic test will not take a single healthy person as sick, and it will even fail to spot a diseased person (low sensitivity).

If a classifier or test gives positive blindly, as mentioned before, it has high sensitivity but low specificity.



## False positive rate

= Positive among all false

False positive rate = $P(positive|false)=1-specificity$

## False negative rate

=Negative among all true

False negative rate = $P(negative|true)=1-sensitivity$

