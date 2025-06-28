# Chapter 2: Statistics, Probability and Noise
In this chapter, we briefly go over statistics and probability. When processing signals, we need to reduce interference, noise, and other unnecessary data. Statistics and probability helps remove these disruptive components and how they apply to the acquired signals.

## Terminologies
A **signal** is a description of how one parameter depends on another parameter. For example, we can measure the voltage over time, when time extends, we can see how it is changing. The **independent variable** is the values that doesn't depend on any other variable (usually the x-axis, time, domain, sample number). The **dependent variable** is the measurement you get from the indepedent variable (usually the y-axis, range, ordinate).

A **continuous signal** is when both of these parameters are assumed to habe a continuous range of values. An example would be the *voltage* that varies with *time*.

A **discrete/digitized signal** is when both parameters are *quantized*. Imagine the conversion from an analog-to-digital signal. Since values in a computer have limits we would need to convert it into the limits in range. So if we have a 12-bit number with a sampling rate of 1000 samples per second. The votlage is curtailed to 4096 ($2^{12}$) possible binary values. 