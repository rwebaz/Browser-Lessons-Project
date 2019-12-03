---
title: Nokogiri Update
layout: default
excerpt: We found a potential security vulnerability in one of the dependencies for your repo ...
hint: The nokogiri dependency defined in the Gemfile dot lock file for this repo has a known critical severity security vulnerability in version range less than 1.8.1
repo: Browser-Lessons-Project
ver_date: 11-26-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Security Issue

> **Hint**. {{ page.hint }}

More to come ...

### GitHub Pages

Please correct the version of the `nokogiri` dependency from 1.7.2 to **1.8.1** in the current `Gemfile` of the subject repo.

Next, target the root folder of the subject repo through the `Finder` in Mac Os High Sierra ...

Follow the following instruction set:

- Right-click over the root folder of the subject repo

- Select `Services`, `New Terminal at Folder`

- Run `Bundle update` from the Terminal window to auto update the `Gemfile.lock` for the repo

- Perform a *pull request* from the current working branch of the repo via the **GitHub Desktop** program

- Merge changes to the remote master

- Go to the settings of the repo and click on the now clear URL for the `docs` folder of the repo.

**Note**. If all has gone correctly, you should see the *GitHub Pages* rendition of your repo open up in a new Chrome browser window.

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:title="Click to Review ..."}{:target="_blank"}

***

{% include patreon-link.md %}
