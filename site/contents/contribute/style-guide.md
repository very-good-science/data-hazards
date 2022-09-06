# Style guide

This is a brief style guide of some ways that we keep content on the repository consistent. 
If you are making changes or additions then please follow these guidelines.

## Writing text

This website uses Myst markdown.
Myst is slightly different to Github-flavoured markdown, and a [cheatsheet for Myst is available here](https://jupyterbook.org/reference/cheatsheet.html)

Page titles should be sentence case.
This means the first word has a captial, and subsequent words are all lower-case.
The one exception to this is the page titles of the Data Hazards themselves, where every word starts with an upper-case letter.

When writing text generally, every new sentence should appear on a new line. 
This makes it easier to see what has been changed between versions. 

## Data Hazards format

Capitalisation of the *D*ata *H*azards *l*abels should be as you see in this sentence (i.e. capital D, captial H, lower-case l for labels).
They may also be called 'the *H*azards' for short, but we prefer the full term to avoid confusion. 

All new Data Hazard labels should use the following structure:

```
># Hazard: Name of the hazard
>
>```{image} ../../images/hazards/hazard-image-name.png
>:alt: A red diamond shaped outline (like a warning sign) with .....
>:width: 250px
>```
>
>## Description
>A description should go here.
>
>## Examples
>- Example 1
>- Example 2
>
>## Safety Precautions
>- Pre-caution 1 
>- Pre-caution 2
```
