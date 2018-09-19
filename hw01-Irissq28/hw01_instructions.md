# STAT 545A Homework 01: Edit README.md and Use R Markdown

## Overview

This assignment was designed to give you practice with:

- Developing of a simple repository with GitHub; perhaps git too
- Authoring in GitHub-flavoured markdown and R markdown
- Coding in R through data exploration
- Generating output from (`.Rmd`) source

using RStudio.

Due by 23:59 Tuesday 2018-09-18, but I **highly recommend** you aim to submit before class. This assignment should go smoothly, but if the computer gods do not smile upon you, we should be able to straighten things out in class or office hours.

As you work on the assignment, you are welcome to work from the browser (i.e., directly on GitHub), but we encourage you to pilot a more powerful workflow:

- Pull from GitHub (just an empty precaution now, but will matter when you collaborate with others).
- Make changes locally to local files -- RStudio is a great Markdown editor! Click Preview to see how it's going to look!
- Save your changes.
- Commit your changes to your repo.
- Push the commit to GitHub.

### Evaluation

The rubrics used for this assignment are:

- Coding style
- Coding strategy
- Achievement, mastery, cleverness, creativity
- Ease of access for instructor, compliance with course conventions for submitted work

For more details on rubrics, see the [assignments](http://stat545.com/Classroom/assignments/) page. 

You'll be creating two types of content, as we elaborate on below (the README and the R Markdown). They are equally weighed.

## Create your hw01 repo

This is the first time STAT 545 is using [GitHub Classroom](https://classroom.github.com/)! GitHub Classroom will make a repository for you, called `hw01-your_github_username`, for you to work on your assignment. __FYI, it is public__. Follow these instructions to get the repo:

1. Sign in to [UBC canvas](https://canvas.ubc.ca).
2. Go to the `hw01` page.
3. You will find a url leading to a page on GitHub Classroom -- go ahead and visit the page and follow the instructions. But note:
    - You'll be asked to find/pair your github username. If it's not on the list, please (1) click "Skip" to skip this step, and (2) fill out the [course survey](https://goo.gl/forms/UPvRA6a9WRod8JPb2) so that you can be added to the roster. 

When you obtain your repository, it should contain this very `.md` file, and a blank `README.md` file.

## GitHub-Flavoured Markdown: edit `README.md`

Your task here is to edit the `README.md` file in your repository to contain a sampler of GitHub-flavoured markdown features.

The beginning of the README should contain a very brief description as to what the repository is, so that an unknowing visitor landing on the repository can orient themselves. You should also help the visitor navigate your repository (in whatever way you think is most appropriate). 

The next piece of information that your README should contain is an introduction to yourself. Here's where you should elaborate and test out various GitHub-flavoured markdown features.

__At the very least__, change `README.md` to something like "This is the repository of Jane Hacker", just to prove you have been there. Practice making a link, for example, to the [main STAT545 webpage](http://stat545.com).

Much better is to introduce yourself, showcasing a suite of GitHub-flavoured markdown functionality (you might find GitHub's [cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) useful for this). 

Here's a [sample readme file](https://github.com/STAT545-UBC/Classroom/blob/master/assignments/hw01/sample_readme.md). The *Help* menu in RStudio will bring up a Markdown Quick Reference at any time.


## R Markdown for Gapminder exploration

Make an R Markdown document that explores a dataset, such as gapminder seen in class. You don't need an extensive exploration in order to get a good grade here; a basic one will do, not unlike the one done in class, which would be considered sufficient (but less so the more verbatim your submission is). Render your R Markdown to the `github_document` output format. Commit both the `.Rmd` and `.md` files and push them to GitHub.

Give this a decent name, such as `hw01_gapminder.Rmd` (which will produce a companion file, `hw01_gapminder.md`).

## Reflection

Once you're done the above, go back to [UBC canvas](https://canvas.ubc.ca/), and find the "Homework 01" page. Here, you should submit a reflection (and, although not required, adding a link to your homework respository would be helpful for the markers). 

Please don't skip this reflection! We really care about this.

Some things you can include:

- A description of how you got the changes into `README.md` on GitHub.
    - Did you edit in the browser at github.com?
    - Did you pull, edit locally, save, commit, push to github.com?
- How did it all work for the R Markdown document?
- You're encouraged to reflect on what was hard/easy, problems you solved, helpful tutorials you read, etc.

## Special Submission Cases

**Are you worried about submitting early, and then wanting to make changes that are included in your submission?**

Don't be. We'll always grade your GitHub repository as it was at the last commit prior to the deadline. Therefore, we encourage you to submit early and often, especially regarding your GitHub repository!

**Want to submit early, and continue making contributions to your repository that you _don't_ want to be graded?**

Just [create a release](https://help.github.com/articles/creating-releases/) of your homework repo, and include the link to this release in your submission, being sure to indicate that this is a special early release that you want graded. Or, even better, just fork the repo.
