---
title: Key Shorts
layout: default
navigation_weight: 8
---
# Key Shorts

The default `shift` + `cmd` + `p` combo *keybinding* allows the end-user to access the **VSC** *command line interface*.

{% include toc-flammarion.md %}

## Shift Command P

The standard set of *Hot Keys* in **Visual Studio Code** include the `shift` + `cmd` + `p` combo *keybinding* used to `Show All Commands`.

### Discover P

From the **Default Keybindings** file, the `shift` + `cmd` + `p` combo *keybinding* invokes the following default method ...

```liquid
{% raw %}
{
  "key": "shift+cmd+p",
  "command": "workbench.action.showCommands"
}
{% endraw %}
```

## Shift Command I

How to change the *Hot Key* for the default method `Insert Snippet` in Visual Studio Code for Mac Os High Sierra.

### Discover I

First, check the inventory of `Keyboard Shortcuts` currently in play at `Code` + `Preferences` + `Keyboard Shortcuts`.

- Next, reduce the field of candidates by entering the following two keywords at the `Keyboard Shortcuts` prompt:

```liquid
{% raw %}
shift cmd
{% endraw %}
```

### Solution

From the `keybindings.json` file located under `Code` + `Preferences` + `Keyboard Shortcuts` ...

- Modify a new `shift` + `cmd` + `i` combo *keybinding* that invokes the (.json) markdown snippet collection in Visual Studio Code, as follows:

```liquid
{% raw %}
{
  "key": "shift+cmd+i",
  "command": "editor.action.insertSnippet",
  "when": "editorTextFocus && editorLangId == 'markdown'",
  "args": {
  "langId": "markdown"
  },
}
{% endraw %}
```

**Note**. If you are unable to engage `IntelliSense` from within your markdown (.md) pages, then use the above workaround to invoke your (.json) markdown snippet collection directly from the **VSC** *command line interface*.

## IntelliSense

`IntelliSense` is provided for JavaScript, TypeScript, JSON, HTML, CSS, Less, and Sass languages in Visual Studio Code (**VSC**).

To obtain `IntelliSense` for your markdown (.md) pages you must install a language *extension*.

This is over and above a simple *linting and style checking* extension.

For example, use the term *Markdown IntelliSense* when querying the **Extensions Marketplace** in **VSC**.

## Last Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
Enjoy the successful output!
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Browser/Source-Browser-Links.htm){:title="Click to Visit the Source Links page of the Browser Lessons Project at GitHub pages"}{:target="_blank"} page of the Browser Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

- The [Assigning Keybindings To Snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets){:title='Click to Visit the Assigning Keybindings To Snippets section of Creating Your Own Snippets in Visual Studio Code'}{:target='_blank'} section of Creating Your Own Snippets in Visual Studio Code. Published © 2018 by [Code.visualstudio.com](https://code.visualstudio.com/docs/){:title='Click to Visit the index of Document pages at Visual Studio Code'}{:target='_blank'}.
