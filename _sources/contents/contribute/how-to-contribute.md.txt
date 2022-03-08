# How to contribute

Depending on what you would like to do there are different ways to get involved. 
Please check out the options below!
If you can't find what you are looking for then [send us an email][dec-email] and we will help!
You can also come to our [open community co-working calls](../events/coworking) if you would like to chat to us about an idea you have had.


## Suggesting new or improved Data Hazards

In the first instance please [start a Discussion with your idea](https://github.com/very-good-science/data-hazards/discussions/new?category=ideas) in the 'Ideas' category.
We can then chat openly on GitHub about the suggestion, and this gives other people the opportunity to weigh-in on any changes we are considering. 
Once changes have been agreed then you can follow the process below for [making changes to the website](#making-changes-to-the-website-content).

If you would rather you can also [email us][dec-email] to discuss.

## Making changes to the website content

This website is based on a tool called [Sphinx](https://www.sphinx-doc.org/en/master/), which allows us to create all our content in Markdown and render it as a website. 
To find the documentation you want to change or add then follow the file path that is indicated by the website link from the `site` folder in the repo. 
To add the changes to the main repository then:

1. [Fork](https://help.github.com/articles/fork-a-repo) this repository to your own GitHub account.  
2. Check that you are happy with the changes by [building the site locally](#build-the-site-locally).  
3. Before submitting your changes, please add a note to the [Change Log](changelog) that describes the change you made.
4. Then, once you've made your changes, submit a [pull request](https://help.github.com/articles/creating-a-pull-request): we'll review it as quick as we can 😄.

If you are fixing an [issue][issues] then please comment on it before you start working so that we don't repeat your work! 

### Build the site locally

In order to build the site locally, you'll need to run the following from your root directory:
`sphinx-build site/ site/_build/` 

These require some Python packages to run. 
You may want to set up a [virtual environment](https://docs.python.org/3/library/venv.html) first, so that you don't install these packages system-wide.
Then you can install the packages using `pip install -r requirements.txt`

## Adding slides
We try to keep all our slides for Data Hazards on our website.

The current process is:
1. (Optional) create slides in powerpoint, upload to Google drive (which will convert it to Google slides) + check formatting (alternatively, create in Google slides)
2. Create a new markdown web page.
2. Publish google slides `File -> Publish to the web -> Embed -> Small`
3. Copy and paste to new markdown web page.
3. Make viewable with link `Share -> Anyone on the internet with this link can view` 
4. Add link to markdown web page.

Recommendations for a process to create html slides that works with myst markdown extremely welcome!

---
[issues]: https://github.com/very-good-science/data-hazards/issues
[dec-email]: mailto:grp-ethicaldatascience@groups.bristol.ac.uk