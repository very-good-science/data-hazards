# Hazard: Difficult To Understand

```{image} ../../images/hazards/difficult-to-understand.png
:alt: A red diamond shaped outline (like a warning sign) with an image of a closed box and a question mark next to it.
:width: 250px
```

## Description

There is a danger that the technology is difficult to understand. 
This could be because of the technology itself is hard to interpret (e.g. neural nets), or problems with it's implementation (i.e. code is not provided, or not documented).

Depending on the circumstances of its use, this could mean that incorrect results are hard to identify, or that the technology is inaccessible to people (difficult to implement or use).


## Examples

__Example 1:__ Deep learning is used to perform [credit-scoring](https://www.moodysanalytics.com/risk-perspectives-magazine/managing-disruption/spotlight/machine-learning-challenges-lessons-and-opportunities-in-credit-risk-modeling) (i.e. could deny people credit), but it is difficult to understand (and therefore check) what these decisions are based on.

__Example 2:__ Even when journals have a policy of having code and data availability, published researchers can be unaware of what they agreed to and resist sharing it, as [this](https://www.pnas.org/content/115/11/2584) paper surveying Science publications shows.

## Safety Precautions

- Make research code Open Source with [an appropriate software license](https://choosealicense.com/) where possible. Your local [Research Software Engineering](https://society-rse.org/) group may be able to help you with this.
- Compare results to white box (explainable) methods such as [Random Forest](https://en.wikipedia.org/wiki/Random_forest) or [Regression](https://en.wikipedia.org/wiki/Regression_analysis), which may perform just as well. 