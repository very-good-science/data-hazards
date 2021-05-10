# Data Hazard labels

[//]: # (TODO: Link to contribution guidelines)

This page contains the Data Hazard labels themselves.
These labels, descriptions, examples, and safety precautions will evolve as we develop the hazard labels with the communities who will use them.
We welcome you to suggest changes via [email](mailto:grp-ethicaldatascience@groups.bristol.ac.uk) or [GitHub](https://github.com/very-good-science/data-hazards).

Each hazard has:
- __Hazard__ image, title, and description which represents and describes the risk.
- __Examples__ to clarify what the hazard covers.
- __Safety Precautions__ - things that we would want to see done **before** the research is deployed.

They are designed to help us think about the different types of hazards

[//]: # (TODO: Add 2 examples for each hazard - with a link if possible)
[//]: # (TODO: Add safety precautions for each hazard - with a link if possible.)

````{panels}
:container: container-fluid
:column: col-4 p-3
:img-top-cls: p-3 bg-warning
:header: bg-warning
:body: bg-warning 
:footer: bg-warning 

:img-top: /images/hazards/general-hazard.png

__Hazard: Data Hazard__

Data Science is being used in this output, and any negative outcome of using this work are not the fault of "the algorithm" or "the software". 

This hazard applies to __all__ Data Science research outputs.

^^^

All other Data Hazard examples could feature as examples here.

+++
__Safety Precautions:__
-  Users of this work should be informed that __the repsonsibility for using this work responsibly and ethically, lies with each person who impliments it in a project or product.__

---
:img-top: /images/hazards/reinforce-bias.png

__Hazard: Reinforces existing biases__

Reinforces unfair treatment of individuals and groups. This may be due to for example input data, algorithm or software design choices, or society at large. 

__Note:__ this is a hazard in it's own right, even if it isn't then used to harm people directly, due to e.g. reinforcing stereotypes.

^^^

__Example 1__: [Natural Language Processing tools can reinforce sexist tropes about women](https://arxiv.org/abs/1607.06520). 

__Example 2:__ [Automated soap dispensers that do not work for black people](https://metro.co.uk/2017/07/13/racist-soap-dispensers-dont-work-for-black-people-6775909/)

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
:img-top: /images/hazards/lacks-community.png

__Hazard: Lacks community involvement__
This applies when technology is being produced without input from the community it is supposed to serve.

^^^

__Example 1:__ Research into cures for Autism generally ([which are not wanted by Austistic people](https://www.theguardian.com/commentisfree/2009/jan/14/autism-health)).

__Example 2:__ Samaritan's Radar app highlighted people who may be struggling to cope on Twitter, and was [withdrawn following wide criticism](https://www.samaritans.org/about-samaritans/research-policy/internet-suicide/samaritans-radar/). 

+++
__Safety Precautions:__
- Ask the people who the works is about if they want this kind of solution, and co-create or [co-produce](https://www.youtube.com/watch?v=6XF0GFDYw3E) research with them as partners.
- Test the effectiveness of the algorithm or technology for different marginalised groups.

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
:img-top: /images/hazards/difficult-to-understand.png

__Hazard: Difficult to understand__
There is a danger that the technology is difficult to understand. 
This could be because of the technology itself is hard to interpret (e.g. neural nets), or it's implementation (i.e. code is hidden and we are not allowed to see exactly what it is doing).

Depending on the circumstances of it's use, this could mean that incorrect results are hard to identify, or that the technology is inaccessible to people (difficult to implement or use).

^^^

__Example 1:__ Google does not make code available for many projects, from it's DeepMind AlphaFold [protein-folding research](https://deepmind.com/blog/article/alphafold-a-solution-to-a-50-year-old-grand-challenge-in-biology) to its' [Search Engine algorithms](https://www.searchenginejournal.com/google-algorithm-history/).

__Example 2:__ Deep learning is used to perform [credit-scoring](https://www.moodysanalytics.com/risk-perspectives-magazine/managing-disruption/spotlight/machine-learning-challenges-lessons-and-opportunities-in-credit-risk-modeling) (i.e. could deny people credit), but it is difficult to understand (and therefore check) what these decisions are based on.

+++
__Safety Precautions:__
- Make research code Open Source with [an appropriate software license](https://choosealicense.com/) where possible. Your local [Research Software Engineering](https://society-rse.org/) group may be able to help you with this.
- Compare results to white box (explainable) methods such as [Random Forest](https://en.wikipedia.org/wiki/Random_forest) or [Regression](https://en.wikipedia.org/wiki/Regression_analysis), which may perform just as well. 

---
:img-top: /images/hazards/direct-harm.png

__Hazard: May cause direct harm__
The application area of this technology means that it is capable of causing direct physical harm to someone, e.g. healthcare, driverless vehicles.

^^^

__Example 1:__ Software running on driverless cars can fail, allowing the car to crash, which can injure or [kill](https://www.nytimes.com/2021/04/18/business/tesla-fatal-crash-texas.html) [people](https://www.bbc.co.uk/news/technology-54175359).

__Example 2:__ If research used as evidence for a clinical trial contained mistakes that undermined the results, this would   

+++
__Safety Precautions:__
- It is even more important that work of this nature is well-tested and that any "bugs" (mistakes in software) are found.  
````

[//]: # (TODO: Add below for doesn't work)
<!--
__Example 2__: Twitter's algorithm to choose the relevant part of an image [consistently chooses to crop out black faces instead of white faces](https://www.theguardian.com/technology/2020/sep/21/twitter-apologises-for-racist-image-cropping-algorithm).
-->