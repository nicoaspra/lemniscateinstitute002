---
title: "Properties and the General Power Rule for Integration"
authornum: 2
author: Engr. Nico O. Aspra, ME, RMP  <br> Engr. Pee Jay N. Gealone
weight: 2
layout: content
prevcontenturl: ../IC-2.1-antiderivatives
nextcontenturl: ../IC-3.2-exponential-and-logarithmic-functions
---


## Introduction
In the previous lesson, we have established that integration (indefinite integral in particular) is simply the reverse of differentiation. Hence, this lesson will investigate the general power rule, which is one of the most common and valuable basic integration processes. 

The general power rule for integration can be associated as the inverse of the general power rule for differentiation.
You can also have an in-depth review of the power rule for differentiation before starting this lesson for a deeper understanding of the topic.

## Properties of Indefinite Integral
Before we start our discussion with the general power rule, let us first introduce the properties of indefinite integrals. These properties are a prerequisite before introducing the different processes of applying integration techniques in a differential function. 

For the following formulas for evaluating indefinite integrals, let $u$, $v$ and $w$ be a function of $x$; $a$ and $n$ as constants; and $C$ as the constant of integration.

{% include tcolorbox.html
    details = "
        \int du &= u+C \\
        \int a\,du &= a\int du \\
        \int (du\pm dv\pm dw) &= \int du \pm \int dv \pm \int dw
    "
%}




- If you could recall, the steps in differentiating using the power rule include multiplying the exponent of the variable to the term then reducing the value of the exponent by one. However, in integration, it is the reverse of that. The first step is adding one to the exponent, then dividing the whole term with the same value of the variable's new exponent.



- Assuming that you have already reviewed the concepts of differentials, we can observe that the general power formula for differentials follows two basic steps: (1) multiplying the function with the original exponent $n$, and (2) subtracting one from the original exponent $n$. Interestingly, it can be observed that we can apply anti-differentiation (integration) through \textit{reversing the steps} mentioned. Thus, for the general power rule for integration, we add one from the exponent $n$ then divide the function with the new exponent $n+1$. Equation \ref{eq:integration - general power rule} shows the formula described.