# Data Hazard labels

This page contains the Data Hazard labels themselves.
These labels, descriptions, examples, and safety precautions will evolve as we develop the hazard labels with the communities who will use them.
We welcome you to suggest changes, so please check our [contribution guidelines](contribute) if you would like to. 

Each hazard has:
- __Hazard__ image, title, and description which represents and describes the risk.
- __Examples__ to clarify what the hazard covers.
- __Safety Precautions__ - things that we would want to see done **before** the research is deployed.

They are designed to help us think about the different types of hazards

````{panels}
:container: container-fluid
:column: col-6 p-3
:img-top-cls: p-3 bg-warning
:header: bg-warning
:body: bg-warning 
:footer: bg-warning 

:img-top: /images/hazards/general-hazard.png

```{link-button} hazards/general-hazard.html
:text: 
:classes: stretched-link
```
__Data Hazard__

Data Science is being used in this output, and any negative outcome of using this work are not the fault of "the algorithm" or "the software". 

This hazard applies to __all__ Data Science research outputs.

---
:img-top: /images/hazards/reinforce-bias.png

```{link-button} hazards/reinforces-biases.html
:text: 
:classes: stretched-link
```
__Reinforces Existing Biases__

Reinforces unfair treatment of individuals and groups. This may be due to for example input data, algorithm or software design choices, or society at large. 

__Note:__ this is a hazard in it's own right, even if it isn't then used to harm people directly, due to e.g. reinforcing stereotypes.

---
:img-top: /images/hazards/classifies-people.png

```{link-button} hazards/ranks-classifies.html
:text: 
:classes: stretched-link
``` 
__Ranks Or Classifies People__

Ranking and classifications of people are hazards in their own right and should be handled with care.

To see why, we can think about what happens when the ranking/classification is inaccurate, when people disagree with how they are ranked/classified, as well as who the ranking/classification is and is not working for, how it can be gamed, and what it is used to justify or explain.

---
:img-top: /images/hazards/environment.png

```{link-button} hazards/high-environmental-cost.html
:text: 
:classes: stretched-link
``` 
__High Environmental Cost__

This hazard is appropriate where methodologies are energy-hungry, data-hungry (requiring more and more computation), or require special hardware that require rare materials. 

---
:img-top: /images/hazards/lacks-community.png

```{link-button} hazards/lacks-community-involvement.html
:text: 
:classes: stretched-link
``` 
__Lacks Community Involvement__

This applies when technology is being produced without input from the community it is supposed to serve.

---
:img-top: /images/hazards/misuse.png

```{link-button} hazards/danger-of-misuse.html
:text: 
:classes: stretched-link
``` 
__Danger Of Misuse__

There is a danger of misusing the algorithm, technology, or data collected as part of this work.

---
:img-top: /images/hazards/difficult-to-understand.png

```{link-button} hazards/difficult-to-understand.html
:text: 
:classes: stretched-link
``` 
__Difficult To Understand__

There is a danger that the technology is difficult to understand. 
This could be because of the technology itself is hard to interpret (e.g. neural nets), or problems with it's implementation (i.e. code is not provided, or not documented).

Depending on the circumstances of its use, this could mean that incorrect results are hard to identify, or that the technology is inaccessible to people (difficult to implement or use).

---
:img-top: /images/hazards/direct-harm.png

```{link-button} hazards/direct-harm.html
:text: 
:classes: stretched-link
``` 
__May Cause Direct Harm__

The application area of this technology means that it is capable of causing direct physical or psychological harm to someone even if used correctly e.g. healthcare and driverless vehicles may be expected to directly harm someone unless they have 100% accuracy.

---
:img-top: /images/hazards/privacy.png

```{link-button} hazards/risk-to-privacy.html
:text: 
:classes: stretched-link
``` 
__Risk To Privacy__

This technology may risk the privacy of individuals whose data is processed by it. 

---
:img-top: /images/hazards/automates-decision-making.png

```{link-button} hazards/automates-decision-making.html
:text: 
:classes: stretched-link
``` 
__Automates Decision Making__

Automated decision making can be hazardous for a number of reasons, and these will be highly dependent on the field in which it is being applied. 
We should ask ourselves whose decisions are being automated, what automation can bring to the process, and who is benefitted/harmed from this automation. 

---
:img-top: /images/hazards/lacks-informed-consent.png

```{link-button} hazards/lacks-informed-consent.html
:text: 
:classes: stretched-link
``` 
__Lacks Informed Consent__

This hazard applies to datasets or algorithms that use data which has not been provided with the explicit consent of the data owner/creator. This data often lacks
other contextual information which can also make it difficult to understand how the dataset may be biased.

````

