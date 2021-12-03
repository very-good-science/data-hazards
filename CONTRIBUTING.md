# Contributing
[//]: # (TODO: Maybe move this to the website!)

Thank you for being interested in contributing to this project! 
Your help is very valuable: to get a handle on the ethical implications of Data Science, we *need* to consider diverse viewpoints! 

## *Types* of contribution
Here are some ways to get involved. We would absolutely love your input on the following:
1. Feedback on our [Data Hazard Labels](https://very-good-science.github.io/data-hazards/contents/materials/workshop/data-hazards.html), we accept suggestions through Issues and Pull Requests✨ here on GitHub, or via [email][dec-email]. For example you might suggest:
    - Ways of rewording Data Hazard Label descriptions or titles.
    - New examples of Data Hazards.
    - New/updated "Safety Precautions" (ways of combatting Data Hazards).
    - Ideas for new Data Hazards.
2. Join one of [upcoming workshops](https://very-good-science.github.io/data-hazards/contents/upcoming-events.html) or (in development) asynchonous mailing lists to provide Data Hazards reviews on different projects.
3. Contribute to any of our [workshop materials](https://very-good-science.github.io/data-hazards/contents/exercises.html) - or ideas for new materials (open an issue or  [email us][dec-email]).
4. Use the Data Hazards materials to reflect on your own work and contribute this as an example to help other people use the 
5. Find [GitHub issue][issues] that you know how to solve, and help us with that!

## *How* to contribute

[//]: # (TODO: Have a guide here to the way that the website is organised)

We will develop these contribution guidelines as we go, including where to look in this repo for different files and so on.
For now, they are a little thin, so if you'd like to help please get in touch with us, please [send us an email][dec-email] and we will help you to find what you're looking for!

### Contributing on GitHub
If you find an [issue][issues] that you'd like to help with, then please:
1. Comment on it before you start working, so we don't repeat work.
2. [Fork](https://help.github.com/articles/fork-a-repo) this repository to your own GitHub account
3. Check that you are happy with the changes by [building the site locally](#build-the-site-locally).
4. Then, once you've made your changes, submit a [pull request](https://help.github.com/articles/creating-a-pull-request): we'll review it as quick as we can 😄.

### Adding slides
We try to keep all our slides for Data Hazards on our website.

The current process is:
1. (Optional) create slides in powerpoint, upload to Google drive (which will convert it to Google slides) + check formatting (alternatively, create in Google slides)
2. Create a new markdown web page.
2. Publish google slides `File -> Publish to the web -> Embed -> Small`
3. Copy and paste to new markdown web page.
3. Make viewable with link `Share -> Anyone on the internet with this link can view` 
4. Add link to markdown web page.

Recommendations for a process to create html slides that works with myst markdown extremely welcome!

### Build the site locally
In order to build the site locally, you'll need to run the following from your root directory:
`sphinx-build site/ site/_build/` 

These require some Python packages to run. 
You may want to set up a [virtual environment](https://docs.python.org/3/library/venv.html) first, so that you don't install these packages system-wide.
Then you can install the packages using `pip install -r requirements.txt`


---
[issues]: https://github.com/very-good-science/data-hazards/issues
[dec-email]: grp-ethicaldatascience@groups.bristol.ac.uk
