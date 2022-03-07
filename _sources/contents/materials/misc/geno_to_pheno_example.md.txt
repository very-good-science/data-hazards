# Example of applied Data Hazards: "Predicting phenotype from genotype"

## The project

There is so much variation in the human population; from how we look to how we function; from our height to the level of calcium in our blood to our chances of getting Alzheimer's. 
These measurable differences between us are called phenotypes. 

Our genotype on the other hand is the variation in our DNA. 
This DNA decides exactly which versions of key proteins get made in our bodies, and these proteins go on to have many functions, from being physical building-blocks of cells, to acting as signals to tell the body to produce other proteins. 
Sometimes the link between genotype and phenotype are straightforward and known (e.g. for eye colour), but we still do not know even one function for most human proteins.

What we do have is a wealth of information about the smaller building blocks of proteins and links between these and known phenotypes, information about the prevalence of different versions of proteins in the human population, and knowledge about which parts of proteins are conserved across the tree of life (and therefore vital to protein functionality).
This information comes from the literature of links between genes or proteins and function or phenotype across many different organisms, not just humans or even just animals.
We can combine this data and use unsupervised learning (clustering and outlier detection) to create scores predicting which phenotypes each protein effects and predict the likelihood of phenotypes for people within a cohort.
These results could be used to reveal links between genotype and phenotype that could find new treatments for diseases. 

The phenotype predictor works by finding people who have an unusual combination of mutations at locations on their DNA that fall in structures with some link to each phenotype. 
This cannot make predictions using DNA that falls outside of protein-coding regions, meaning that it uses ~2% of the genome to make these predictions.
It is not expected to be accurate for all phenotypes. 
It is not a diagnostic tool, but rather it is supposed to be used as a research tool to find complex traits (which need a combination of mutations) to study further.

The algorithm has been designed and tested for computational efficiency, and is not resource-intensive.

## How to apply the hazards
Go through [the list of hazards](../../data-hazards.md) and try to apply each hazard, looking at the examples and description for clarifications. 

## The applied hazards

```{list-table}
* - Hazard Name
  - Does the hazard apply?
  - Reason
* - `Contains Data Science`
  - Yes
  - Uses data, makes a prediction, uses unsupervised learning
* - `Reinforces Existing Biases`
  - Yes
  - Project does not check that the algorithm works just as well for minority groups, who may be less likely to be represented in the input data. Therefore in a worst-case scenario, this could happen. 
* - `Classifies or ranks people`
  - Yes
  - People are scored (ranked) for different phenotypes, including phenotypes relating to mental health and disability.
* - `High Environmental Cost`
  - No
  - The algorithm has been tested for computationally efficiency and does not require many computational resources.
* - `Lacks Community Involvement`
  - Yes
  - The communities of people with the phenotypes have no current involvement in this process. 
* - `Danger of misuse`
  - Yes
  - The phenotype predictor is not expected to be accurate for all phenotypes, but It could even be used to try to predict phenotypes that are caused by the environment or regions of DNA it does not consider, if these are defined as genetic phenotypes in other literature. 
* - `Difficult to understand`
  - Yes
  - Doesn't use black box machine learning (e.g. deep learning), but has closed source code and a complicated data pipeline.
* - `May cause direct harm`
  - No
  - Could not cause direct harm unless misused.
* - `Privacy`
  - Yes
  - Individual's genetic data is required to run the phenotype predictor. This has many privacy risks, for example identification, use by insurers, being contacted by unknown relatives.
* - `Automates decision-making`
  - No
  - The phenotype predictor is not a diagnostic tool.
* - `Lacks informed consent`
  - No
  - The predictor has used datasets from 1000 genomes project, ALSPAC, and genetrainer. Although these individuals were not specifically aware that their data would be used in this way, they were made aware that their data could be used for a range of research.
```

## Applying the safety precautions
The applied hazards can then be used to help the researcher create a list of safety precautions for their project using those provided on the [hazards page](../../data-hazards.md). 
In this case the safety precautions might be:
- Clearly lay out responsibilities for research and adoption/deployment.
- Test the algorithm's efficacy separately for minority groups.
- Curate the phenotypes predicted on by the released software. In deployment: ensure this information is only shared with users themselves, and that they have assistance interpreting the scores.
- Phenotypes chosen as case-studies for research should be chosen carefully and involve communities where relevant. For it to be deployed, the list of conditions that it predicts should be curated manually depending on the community. This would prevent situations, such as the algorithm being used to predict whether unborn children are likely to be neurodivergent. 
- State the limitations of the method clearly, retest it if it is used outside the research context.
- Increase documentation, and make the source code open if possible.
- Informed consent of any additional users/participants, relating to privacy as well as other aspects. Store data carefully/briefly.
