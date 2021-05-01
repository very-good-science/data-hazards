# Data Hazard labels

[//]: # (TODO: Link to contribution guidelines)

This page contains the Data Hazard labels themselves.
These labels, descriptions, examples, and safety precautions will evolve as we develop the hazard labels with the communities who will use them.
We welcome you to suggest changes via [email](mailto:grp-ethicaldatascience@groups.bristol.ac.uk) or [GitHub](https://github.com/very-good-science/data-hazards).

Each hazard has:
- __Hazard__ image, title, and description which represents and describes the risk.
- __Examples__ to clarify what the hazard covers.
- __Safety Precautions__ - things that we would want to see done **before** the research is deployed.

[//]: # (TODO: Add 2 examples for each hazard - with a link if possible)
[//]: # (TODO: Add safety precautions for each hazard - with a link if possible.)

````{panels}
:container: container-fluid
:column: col-4 p-3
:img-top-cls: p-3 bg-warning
:header: bg-warning
:body: bg-warning 
:footer: bg-warning 


---
:img-top: /images/hazards/general-hazard.png

__Hazard: Data Hazard__

Data Science is being used in this output, and any negative outcome of using this work are not the fault of "the algorithm" or "the software". __The repsonsibility for using this work responsibly and ethically, lies with each person who impliments it in a project or product.__

This hazard applies to __all__ Data Science research outputs.

^^^

All other Data Hazard examples could feature as examples here.

+++
__Safety Precautions:__
- 

---
:img-top: /images/hazards/reinforce-bias.png

__Hazard: Reinforces existing biases__

Reinforces unfair treatment of individuals. This may be due to for example input data, algorithm or software design choices, or society at large. 

__Note:__ this is a hazard in it's own right, even if it isn't then used to harm people directly, due to e.g. reinforcing stereotypes.

^^^

__Example 1__: [Natural Language Processing tools can reinforce sexist tropes about women](https://arxiv.org/abs/1607.06520). 


+++
__Safety Precautions:__
- Test the effect of the algorithm for different marginalised groups, considering different definitions of [bias]() and [fairness]().
- Think about the input data, what intrinsic bias it contains, and how this can be reduced (for example by having a more representative data set).
- Think about the bias of the algorithm, what intrinsic bias it contains, and how this can be reduced.



---
:img-top: /images/hazards/classifies-people.png

__Hazard: Ranks or classifies people:__
 
Ranking and classifications of people are hazards in their own right and should be handled with care.

To see why, we can think about what happens when the ranking/classification is inaccurate, when people disagree with how they are ranked/classified, as well as who the ranking/classification is and is not working for, how it can be gamed, and what it is used to justify or explain.

^^^

__Example 1:__ [Facial recognition categorising human images by sexual orientation](https://www.bbc.co.uk/news/technology-41188560). 

__Example 2:__ [School league tables](https://www.bristol.ac.uk/media-library/sites/cmm/migrated/documents/limitations-of-league-tables.pdf) (which rank the perfmance of schools).

+++
__Safety Precautions:__
- Test the effect of the algorithm or technology for different marginalised groups. 
- Be transparent about what the weaknesses of the algorithm and technology are: test how can it be fooled. 
- Consider alternatives to ranking/classification, for example treating people equally, increasing resources for the issue at hand, or allowing people to self-select.

---
:img-top: /images/hazards/environment.png

__Hazard: High Environmental Cost__

This hazard is appropriate where methodologies are energy-hungry, data-hungry (requireing more and more computation), or require special hardware that require rare materials. 

^^^

__Example 1:__ Cryptocurrency requires [vast energy usage](https://www.bbc.co.uk/news/technology-56012952)

__Example 2:__ Language models [require larger and larger datasets](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf)

+++
__Safety Precautions:__
- Consider in what circumstances it is worthwhile to use this type of methodology.
- Consider future work that would reduce the need to use increasingly more resources.
---

:img-top: /images/hazards/ignores-opposes-needs.png

__Hazard: Ignores or opposes needs__
This includes the hazard of the technology/method not working for a certain group, as well as the hazard of the work being against the wishes of a community that it is supposed to serve.

^^^

__Example 1:__ Research into cures for Autism generally ([which are not wanted by Austistic people](https://www.theguardian.com/commentisfree/2009/jan/14/autism-health)).

__Example 2:__ [Automated soap dispensers that do not work for black people](https://metro.co.uk/2017/07/13/racist-soap-dispensers-dont-work-for-black-people-6775909/)

+++
__Safety Precautions:__
- Ask the people who the works is about if they want this kind of solution, and co-create or [co-produce](https://www.youtube.com/watch?v=6XF0GFDYw3E) research with them as partners.
- Test the effect of the algorithm or technology for different marginalised groups.

---
:img-top: /images/hazards/misuse.png

__Hazard: Danger of misuse__
There is a danger of misusing the algorithm, technology, or data collected as part of this work.

^^^

__Example 1:__ Statistical method to do impossible tasks, for example [predicting future human behaviour]().

__Example 2:__ The collection of a large data set of individuals, which could be hacked, or used for other purposes.

+++
__Safety Precautions:__
- Write clear instructions about in what circumstances the algorithm/technology will work or give valid answers and present these wherever the work is presented.
- If work is piloted outside of this context, it must be re-tested.
- Follow data governance guidelines.

---


````

[//]: # (TODO: Add below for doesn't work)
<!--
__Example 2__: Twitter's algorithm to choose the relevant part of an image [consistently chooses to crop out black faces instead of white faces](https://www.theguardian.com/technology/2020/sep/21/twitter-apologises-for-racist-image-cropping-algorithm).
-->