# Data Hazards: using worst case scenarios to make data ethics relevant to abstract technologies

```{admonition} Context and paths forwards

__Authors__: Natalie Thurlby (Data Scientist, JGI) and Nina Di Cara (PhD student, GW4 BioMed MRC DTP - AI and Data Science)

__Context__:  We organise [Data Ethics Club](http://www.bristol.ac.uk/golding/events/2021/data-ethics-club---february-17.html) a discussion group about Data Science and Ethics. 
Through this, we were invited to write an opinion piece about what we've learned so far. 
It will be about data scientist researcher's place in considering ethics, particularly about how it's an interdisciplinary problem that we're not very well trained for, and also about where we can make interventions. 

What's written here (Data Hazards) is a research idea that has come from this discussion, and is one way we thought that we could approach the problems we have faced in applied data ethics. 
Getting feedback on this idea at this early stage would be really invaluable to us. 
Thanks so much for reading! 

__Paths forwards__:

We would really welcome:
- feedback on the idea at this stage, for example in relation to:
    - data hazard labels themselves
    - workshop format
    - how to include, centre, credit, and celebrate the expertise of social science, political science, historian, and other arts colleagues. 
    - reading suggestions for us (particularly re: recommended futures planning tool-kits)
- offers of collaboration, both academically and organisationally, for example:
    - offers to involve institute/organisation networks
    - offers to help with workshop organisation
    - offers to act in an advisory capacity on this work
    - offers to include the finalised Data Hazards resources as part of a publishing or funding process
```

## The problem
Data science is having a profound and often deeply unfair impact on people's lives.
A typical route for this impact [can look like this](https://www.gov.uk/government/publications/cdei-publishes-review-into-bias-in-algorithmic-decision-making/main-report-cdei-review-into-bias-in-algorithmic-decision-making): `researcher --> adoption by a tech company --> sale to a public service provider`. 

Data science researchers lack the incentives, training, resources, or support, to truly consider the societal impact of their work alone.
They can also be [extremely reluctant to consider ethics particularly at an early, abstract stage](https://twitter.com/pmddomingos/status/1336187141366317056). 
This scrutiny is also not often provided by Institutional Review Boards (IRBs), whose focus tends to be on the protection of human participants in research rather than distant negative outcomes.
But by leaving ethical review until deployment, we leave open the door to adopters selling public service providers "solutions" without awareness of potential impacts.

We have skilled colleagues considering the impacts of technologies through different lenses.
Unfortunately data scientists often do not read this work.
Partly because it is often published separately and partly because they do not see ethics as part of their day-to-day roles.
Often it can also be difficult for them read (e.g. due to unfamilar and specialised language).

Data scientists should, and should be supported and incentivised to, consider ethics early, **and** to listen to outside perspectives on their work.

## The idea

### Consider worst-case scenarios...
No single intervention will be able to solve this problem, but there is a need for action we can take *as researchers* to interrupt the ethics-free pipeline from `research --> human impact`.

Considering worst case scenarios is one part of this puzzle. 
Worst case scenarios free us from trying to predict the future: we're not saying that something *will* happen.
This allows us to explore some darker possibilities even if we have skin in the game. And once we've considered them, we know what we're trying to avoid.

There are two important components to this: 
1. Getting the data scientists themselves to reflect on what they are doing
2. Allowing them to learn from others' perspectives on what they are doing

### ...through Hazard labels
We will develop an approachable framework for doing this, which mirrors the familiar COSHH chemical hazard labels, in order to provide:
- a starting point for thinking about *what* might happen, to reduce barriers to the task for the uninitiated. However they are only applied to research by considering *why* the labels fit.
- a controlled joint vocabulary with which to talk about the problem, to aid interdisciplinary communication.
- a very visible output to the process: an instruction to "handle with care" that data scientists can ask people to respect going forwards; something that can be included on slides, papers, or as additions to software licenses.
- a way for potential adopters (at any subsequent stage) to be made aware of the responsibility they take on when they apply the technology.

```{danger} 
__Data Hazards are not designed for mature technologies__.

Data Hazards are designed for abstract, non-mature technologies - for research that is **not** ready for deployment yet.

When technologies are ready for deployment, there are other things that should be done, for example including the perspectives of people who will be effected by the technology through participatory co-creation of research.
```

## What we will make and do

### Overview
We hope to create approachable and attractive materials that will help lower the barrier to considering worst case scenarios, including:
- hazard label materials (artwork, labels, descriptions)
- resources for how to apply them (e.g. sheets to work through, via a workshop or mailing list)
- running workshops to test these activities and get feedback.
- running our own longer-term mailing list or regular meeting/workshop, so that there is a place where data scientists can get this kind of feedback on their work.

In order to share the work more widely we aim to publish the outputs (final product as described and its evaluation).

### Hazards

We plan to keep to a small number of hazard labels to begin with, to keep the activities focused and manageable. 
Our current list includes:
- Automates decision-making
- Classifies or ranks people
- High environmental cost
- Reinforces existing biases
- Threatens privacy
- Difficult to interpret

Each will have a jargon-free name and description and examples of problems to look out for. 
For example, for "Automating decision-making" you might want to consider if you "treat unusual data differently".

### Activities
To apply these data hazard labels, we will develop short activities that take inspiration for specific activities (e.g. worksheets or discussion activities) from existing horizon-scanning and foresight analyses.
For example one guide for applying the labels might look like:
1. Imagine all potential applications of the technology
2. Who will be effected by these applications?
3. How could these people be negatively effected in a worst case scenario?
4. Which labels apply and why?
5. Are there any worst case scenarios are not covered by the labels? What would a hazard label for this scenario look like?

The last step (5) will help us to refine the hazard labels, but we also think there will always be a space for more free-form or specific concerns.

### Miscellaneous
The outputs will also include some miscellaneous resources, e.g.
- How to present your Data Hazards (e.g. template slides and GitHub badges), and credit the work that other people do in helping you to consider the ethical implications.
- Materials for running your own Data Hazards workshop or mailing list
- Resources for funders/publishers
- Recommendations for who data scientists might want to approach to help them critically evaluate their work, such as those based in sociology or philosophy. 

### Workshop Plans
We hope to run two short (60-90 minute) workshops to test out the proposed [resources and activities](#Activities) and get feedback on them. 
For example, we hope these workshops will help us streamline the process, identify missing Data Hazard labels, and identify when this process is valuable and to whom.

Our plans for this are as follows:
- In advance, ask data scientists to volunteer project ideas.
- Data scientists independently apply hazard labels to their own work.
- Then (at the workshop) the data scientists will present their project to an interdisciplinary audience.
- The audience will apply hazard labels individually.
- Then, in smaller groups using a method to encourage reflection called ['the reflective team'](https://link.springer.com/referenceworkentry/10.1007/978-3-319-15877-8_324-1), each data scientist will listen as the audience discusses the labels for their project. The data scientist is only allowed to answer factual questions (i.e. not defend themselves) until the discussion is over. The purpose of this exercise is for the data scientist to hear potentially new perspectives on the ethical implications of their work.
- After this process, we will ask both data scientists and the audience to re-evaluate the hazard labels and feed back on the process of deciding them.

The first workshop will invite an academic audience, while the second will also invite tech companies, and the general public. 
We hope for these both to take place in 2021 in the Summer and Autumn. 

### JGI Seed-corn funding
We plan to use the finalised Data Hazards resources (after workshop feedback) in the Jean Golding Institute institute for Data Science's annual seed-corn funding (November 2021).