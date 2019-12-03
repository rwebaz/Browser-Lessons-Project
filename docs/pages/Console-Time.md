---
title: Console Time
layout: default
excerpt: A modern browser method to measure the approximate amount of time in milliseconds ms required to execute a block of code ...
hint: Both the console.time() and the complimentary console.timeEnd() methods accept one like parameter to fill each respective argument.
repo: Browser-Lessons-Project
ver_date: 11-26-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Parameter Label

> **Hint**. {{ page.hint }}

A value of the `String` type ie.) a *label* that identifies the test being run on the code block between the two methods, as follows:

```javascript
{% raw %}
console.time("checkpi");
// Declare three variables
var pia = 3.14159265359;
var pib = 3.14159265359;
var pic = "3.14159265359";
// An IFFE
(function() {
  var test = (pia == pib);
}());
console.timeEnd("checkpi");
{% endraw %}
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Chad Adams [[1](#CHADADAMS){:.red}].

1. {:#CHADADAMS}[Mastering Javascript High Performance](https://www.packtpub.com/web-development/mastering-javascript-high-performance){:title="Click to Visit the Landing page for Mastering Javascript High Performance by Chad Adams"}{:target="_blank"} by Chad Adams. Published © 2015 by [PACKTpub.com](https://www.packtpub.com/){:title="Click to Visit the Home page of PACKT Publishing"}{:target="_blank"}.

***

{% include patreon-link.md %}
