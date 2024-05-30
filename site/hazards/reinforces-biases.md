# Hazard: Reinforces Existing Biases

```{image} ../images/hazards/reinforce-bias.png
:alt: A red diamond shaped outline (like a warning sign) with a dark head and shoulders, who has a white triangle in their mind. They are looking out at a black circle, a black square and a larger white triangle just ahead of them. This indicates that the largest shape is the one that they think of. 
:width: 250px
```

## Description

Reinforces unfair treatment of individuals and groups. This may be due to for example input data, algorithm or software design choices, or society at large. 

__Note:__ this is a Hazard in it's own right, even if it isn't then used to harm people directly, due to e.g. reinforcing stereotypes.


## Examples

__Example 1__: [Natural Language Processing tools can reinforce sexist tropes about women](https://arxiv.org/abs/1607.06520). 

__Example 2:__ [Automated soap dispensers that do not work for Black people](https://metro.co.uk/2017/07/13/racist-soap-dispensers-dont-work-for-black-people-6775909/)

__Example 3:__ [UK Passport facial recognition checks do not work for people with dark skin](https://www.bbc.co.uk/news/technology-49993647)

## Safety Precautions

- Test the effect of the algorithm for different marginalised groups, considering different definitions of [bias]() and [fairness]().
- Think about the input data, what intrinsic bias it contains, and how this can be reduced (for example by having a more representative data set).
- Think about the bias of the algorithm, what intrinsic bias it contains, and how this can be reduced.
- Do not [deploy tools that are know to reinforce biases against particular groups](https://www.bbc.co.uk/news/technology-49993647) (for instance, systemic racism).
