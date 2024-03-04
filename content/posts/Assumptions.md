+++
authors = ["Blue Bird"]
title = "About Assumptions in Statistics"
date = "2024-02-10"
math = true
tags = [
    "Assumption",
    "Normality",
    "homoscedasticity",

]
categories = [
    "Biostats",
]

+++



Assumption is a common concept in statistical analysis,  such as normality and homoscedasticity assumption for general linear models, proportional odds assumption for ordinal regression, proportional hazard assumption for cox regression.

Checking assumptions is different with making other statistical conclusions. 

**Firstly, assumptions hold as long as no evidence against them.** We do not have to show evidence to support the assumptions. In stead, we only need to show that there is no obvious evidence against the assumptions. To understand this, we may use an example in legal system. In a court, the accused is assumed to be not guilty until the prosecutor gives sufficient evidence to prove that the accused is guilty. This is called "Presumption of Innocence". The accused does not need to collect evidence to prove that he or she is not guilty. 

Assumptions in statistics are similar to presumptions in legal system. When we check normality, we do not prove normality, but show no existed evidence shows the violation of normality.

**Secondly, when hypothesis tests are used to check assumptions, the assumption is usually put in the null hypothesis**, such as 
$$
H_0: \text{Normality holds}
$$
vs
$$
H_1: \text{Violation of normality}.
$$

However, when we try to make other statistical conclusions, we usually put what we want to prove in the alternative hypothesis, such as 
$$
H_0: \text{the new treatment has no effect}
$$
vs
$$
H_1: \text{the new treatment is effective}.
$$
**Last by not least, the result from assumption checking is usually a weak conclusion** compared with other statistical conclusions. For example, normality assumption holds does not mean there is evidence to support the normality of the data. We do not need to control power and confidence level for normality checking, because we are not proving normality. Power and confidence level are only needed for making strong conclusion, such as "outcomes are different among treatment groups".

