# Synthetic Biology Data Hazard: Uncertain Completeness of Source Data 

```{image} ../images/hazards/uncertain-completeness.png
:alt: A red diamond shaped outline (like a warning sign) containing three puzzle pieces that are not connected together.
:width: 250px
```

## Description

Underlying data is of an uncertain completeness and have missing values that causes biased results.

## Examples

__Example 1__: Whole-cell models which attempt to use all the data available, but which may be limited. Protein design often builds on sequences on those proteins so far seen, which may bias design software.

## Safety Precautions

Enrich data sets with missing data or attempt to correct for known biases.