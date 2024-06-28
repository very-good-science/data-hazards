# Data Hazard labels

On this page you can see an overview of the current Data Hazards with short descriptions. Click on each for their full information.
Sub-headings also present Hazards which serve as 'expansion packs' for those using Data Hazards in specific fields. 
We welcome you to suggest changes, so please check our [contribution guidelines](contribute) if you would like to or scroll down for current suggestions below.

You can [download a printable set of the core Data Hazards cards here](_static/DataHazards_PrintableCards.pdf). 

Each individual Data Hazard page contains: 
- A __title__, __description__ and __icon__ to describe the Hazard.
- __Examples__ to clarify what the hazard covers.
- __Safety Precautions__ as suggestions of how Hazards could be mitigated.

:::{dropdown} Why are the Hazard Labels designed this way?
:color: success

Please know that __we don't want these labels to scare anyone away from considering ethics or from doing data science__, and we will do everything that we can to make applying Data Hazards labels as welcoming and approachable as possible, but also have some good reasons for choosing these images.
   
We chose this format because of the similarity to [COSHH hazard labels](https://www.hse.gov.uk/chemical-classification/labelling-packaging/hazard-symbols-hazard-pictograms.htm) - hazard labels for chemicals.
We made this choice because we want a similar response from people:
1. Attention-grabbing, asking people to stop and think, and take the safety precautions seriously, rather than as an optional extra.
2. We're asking people to __"handle with care"__, not to stop doing the work. We still use chemicals, but we think about how it can be done safely and how to avoid emergencies.
3. They are familiar, especially to scientists, who (within universities) tend to have the least experience of applying ethics.
:::

## Version 1.1

<!--FYI The numbers after {grid} below refer to the number of columns that should display for xmall (1), small (2), med (3) and large screens (3) -->

:::::{grid} 1 2 3 3
:margin: 4 4 0 0
:gutter: 2

::::{grid-item-card} General Data Hazard
:img-top: images/hazards/general-hazard.png
:img-alt: A red diamond shaped outline (like a warning sign) with an exclamation mark in the middle.
:link: /hazards/general-hazard
:link-type: doc

Data Science is being used in this output, and any negative outcome of using this work are not the fault of "the algorithm" or "the software". 
::::

::::{grid-item-card} Automates Decision Making
:img-top: /images/hazards/automates-decision-making.png
:img-alt: A red diamond shaped outline (like a warning sign) with two connected cogs that have arrows coming out of the top of them.
:link: hazards/automates-decision-making
:link-type: doc

Automated decision making can be hazardous for a number of reasons, and these will be highly dependent on the field in which it is being applied. 
::::

::::{grid-item-card} Danger Of Misuse
:img-top: /images/hazards/misuse.png
:img-alt: A red diamond shaped outline (like a warning sign) with a hammer raised above a bent screw in the middle.
:link: hazards/danger-of-misuse
:link-type: doc

There is a danger of misusing the algorithm, technology, or data collected as part of this work.
::::

::::{grid-item-card} Difficult to Understand
:img-top: /images/hazards/difficult-to-understand.png
:img-alt: A red diamond shaped outline (like a warning sign) with an image of a closed box and a question mark next to it.
:link: hazards/difficult-to-understand
:link-type: doc

This may apply if the technology itself is hard to interpret (e.g. neural nets), or documentation is poor/unavailable.
::::

::::{grid-item-card} High Environmental Cost
:img-top: images/hazards/environment.png
:img-alt: A red diamond shaped outline (like a warning sign) with an image of a globe on fire in the middle.
:link: hazards/high-environmental-cost
:link-type: doc

Indicates methodologies that are energy-hungry, data-hungry, or require special hardware with rare materials. 
::::

::::{grid-item-card} Lacks Community Involvement
:img-top: /images/hazards/lacks-community.png
:img-alt: A red diamond shaped outline (like a warning sign) with figures in the middle who have a speech bubble above their heads with a big cross through it.
:link: hazards/lacks-community-involvement
:link-type: doc

This applies when technology is being produced without input from the community it is supposed to serve.
::::

::::{grid-item-card} Lacks Informed Consent
:img-top: /images/hazards/lacks-informed-consent.png
:img-alt: A red diamond shaped outline (like a warning sign) containing a magnifying glass hovering over a cross on a piece of paper.
:link: hazards/lacks-informed-consent
:link-type: doc

This hazard applies to datasets or algorithms that use data which has not been provided with the explicit consent of the data owner/creator. 
::::

::::{grid-item-card} May Cause Direct Harm
:img-top: /images/hazards/direct-harm.png
:img-alt: A red diamond shaped outline (like a warning sign) with a skull in the middle.
:link: hazards/direct-harm
:link-type: doc

The application area of this technology means that it is capable of causing direct physical or psychological harm to someone even if used correctly.
::::

::::{grid-item-card} Ranks Or Classifies People
:img-top: images/hazards/classifies-people.png
:img-alt: A red diamond shaped outline (like a warning sign) with three people standing on a podium of first, second and third place.
:link: hazards/ranks-classifies
:link-type: doc

Ranking and classifications of people are hazards in their own right and should be handled with care.
::::

::::{grid-item-card} Reinforces Existing Biases
:img-top: images/hazards/reinforce-bias.png
:img-alt: A red diamond shaped outline (like a warning sign) with a dark head and shoulders, who has a white triangle in their mind. They are looking out at a black circle, a black square and a larger white triangle just ahead of them. This indicates that the largest shape is the one that they think of. 
:link: hazards/reinforces-biases
:link-type: doc

Reinforces unfair treatment of individuals and groups. This may be due to for example input data, algorithm or software design choices, or society at large.
::::

::::{grid-item-card} Risk to Privacy
:img-top: /images/hazards/privacy.png
:img-alt: A red diamond shaped outline (like a warning sign) with a picture of a surveillance camera in the middle.
:link: hazards/risk-to-privacy
:link-type: doc

This technology may risk the privacy of individuals whose data is processed by it.
::::

:::::

### Extensions for Synthetic Biology

[Zelenka, Natalie R., et al. "Data hazards in synthetic biology." _Synthetic Biology_ (2024): ysae010.](https://doi.org/10.1093/synbio/ysae010) 

<!--FYI The numbers after {grid} below refer to the number of columns that should display for xmall (1), small (2), med (3) and large screens (3) -->

:::::{grid} 1 2 3 3
:margin: 4 4 0 0
:gutter: 2

::::{grid-item-card} Uncertain Accuracy of Source Data
:img-top: images/hazards/uncertain-accuracy.png
:img-alt: A red diamond shaped outline (like a warning sign) with a target symbol in the middle.
:link: /hazards/uncertain-accuracy
:link-type: doc

The accuracy of the underlying data is not known and so its use may lead to erroneous results or introduce bias.
::::

::::{grid-item-card} Uncertain Completeness of Source Data
:img-top: /images/hazards/uncertain-completeness.png
:img-alt: A red diamond shaped outline (like a warning sign) containing three puzzle pieces that are not connected together.
:link: hazards/uncertain-completeness
:link-type: doc

Underlying data is of an uncertain completeness and have missing values that causes biased results.
::::

::::{grid-item-card} Integration of Incompatible Data
:img-top: /images/hazards/incompatible-data.png
:img-alt: A red diamond shaped outline (like a warning sign) containing two arrows coming in from different directions that point to an exclamation mark.
:link: hazards/incompatible-data
:link-type: doc

Data of different types and/or sources are being used together that may not be compatible with each other.
::::

::::{grid-item-card} Capable of Ecological Harm
:img-top: /images/hazards/ecological-harm.png
:img-alt: A red diamond shaped outline (like a warning sign) with a dead fish in a stream next a bare tree.
:link: hazards/ecological-harm
:link-type: doc

This technology has the potential to cause broad ecological harm, even if used correctly.
[Image adapted from the [Health and Safety Executive](https://www.hse.gov.uk/chemical-classification/labelling-packaging/hazard-symbols-hazard-pictograms.htm) under the [Open Government License 3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)]
::::

::::{grid-item-card} Potential Experimental Hazard
:img-top: /images/hazards/experimental-hazard.png
:img-alt: A red diamond shaped outline (like a warning sign) with a flask containing an exclamation mark.
:link: hazards/experimental-hazard
:link-type: doc

Translating technology into experimental practice can require safety precautions.
::::

:::::

## Future development

Suggestions for future versions of the Data Hazard labels are curated as GitHub Issues. [Click here to see the current suggestions.](https://github.com/very-good-science/data-hazards/labels/hazard-label-idea) 


## Change log

The change log records when changes that have been made to the project and gives a brief description of what the changes were. 
The change log started in March 2022. 
The most recent changes are at the top of the list. 

<!-- Example change log entry

## DD-MM-YYYY: <10 words to summarise change
More detailed paragraph (~100 words is more than enough!) that describes the changes in more detail and their impact.  
[Your name](link to your github profile) -->

__21.06.2024: v1.1 - Add Synthetic Biology Hazard labels__
Changes made by [@ninadicara](https://github.com/ninadicara) to reflect new additions formally proposed by
authors of [the paper in Synthetic Biology](https://doi.org/10.1093/synbio/ysae010).

__29.05.2024: Put labels in alphabetical order__
[@ninadicara](https://github.com/ninadicara)  


__06.12.2022: Update new Hazard labels__
[@ninadicara](https://github.com/ninadicara)  
Updated all the images of the Hazards with our new labels designed by the amazing [Yasmin Dwiputri](http://yasmindwiputri.com/)! 


__07.03.2022: Move Data Hazards to individual pages__
[@ninadicara](https://github.com/ninadicara)  
Moved all of the Hazards to their own individual pages, and linked them from the original sphinx panels. 
Also capitalised all of the names so that they are consistently named. 
This should make it easier for people to contribute to a single Hazard and record their contribution against it :) 



