---
title: Definition List
layout: default
excerpt: Place the introducing line of text ie.) the 'tagline' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Browser-Lessons-Project
ver_date: 11-26-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Solar

> **Hint**. {{ page.hint }}

More to come ...

### Fence Code

```html
<hgroup class="text-left">
<h3>Solar Page</h3>
</hgroup>
<hr class="green-groove" />

<p>
<span>Welcome! This is the Solar page for the <b>Carbon Free Footprint</b> project.</span>
</p>

<p>
<span>This page has been tested for mobile responsiveness on a Galaxy S5 Smartphone emulator at a width of 360px.</span>
</p>
<hr class="green-groove" />

<h4>Solar Panels</h4>

<p>
<span>More to come ...</span>
</p>

<!-- Output onclick the result of the js function -->
<form role="form">
<div class="form-group">
<label>
<input id="1" type="button" value="Click this button" />
</label>
</div>
</form>
<output>x</output>

<h4>Vertical Definiton List</h4>
<dl class="">
<dt>Data Title</dt>
<dd>Actual Data</dd>
<dd>Actual Errata</dd>
<dd><a href="#" title="Click to Visit Same" target="_self">Hyperlink to Same Page</a></dd>
</dl>

<!-- Comment out Horizontal Definiton List
<h4>Horizontal Definiton List</h4>
<dl class="dl-horizontal"><dt>Data Title</dt><dd>Actual Data</dd></dl> -->

<h4>Vertical Buttons</h4>
<!-- Comment out default ( medium ) renderings 
<div class="btn-group-vertical">
<button type="button" class="btn btn-default btn-lg">Default</button>
<button type="button" class="btn btn-default btn-block">Default</button>
<button type="button" class="btn btn-default btn-sm">Default</button>
<button type="button" class="btn btn-default btn-xs">Default</button>
<div /> -->

<div class="btn-group-vertical btn-group-lg">
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-link">Link</button>
</div>

<h4>Split Drop-down Menu</h4>
<div class="btn-group-lg">
<!-- There is no class in Bootstrap 3.3(7) to force a 'drop-up' -->
<button type="button" class="btn btn-default"><span>Landraces</span>
<button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown">
<i class="caret" ></i>
</button>

<ul class="dropdown-menu" role="menu">
<li><a href="#">Ruderalis</a></li>
<li><a href="#">Sativa</a></li>
<li><a href="#">Indica</a></li>
<li class="divider"></li>
<li><a href="#">Learn</a></li>
</ul>
</button>
</div>
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:title="Click to Review ..."}{:target="_blank"}

***

{% include patreon-link.md %}
