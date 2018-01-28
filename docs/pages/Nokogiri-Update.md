---
title: Nokogiri Update
layout: default
navigation_weight: 8
---
# Nokogiri Update

"We found a potential security vulnerability in one of the dependencies for your repo."

{% include toc-flammarion.md %}

## Nokogiri Security Issue

The `nokogiri` dependency defined in the `Gemfile.lock` for this repo has a known critical severity security vulnerability in version range < 1.8.1;

## GitHub Pages

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

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
Enjoy the successful output!
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Shell/Source-Shell-Links.htm){:title="Click to Visit the Source Links page of the Shell Lessons Project at GitHub pages"}{:target="_blank"} page of the Shell Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.










