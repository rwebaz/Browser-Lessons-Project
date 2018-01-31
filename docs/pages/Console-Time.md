---
title: Console Time
layout: default
navigation_weight: 3
---
# Console Time

A modern browser method to measure the approximate amount of time in milliseconds (ms) required to execute a block of code.

{% include toc-flammarion.md %}

## Parameter Label

Both the `console.time()` and the complimentary `console.timeEnd()` methods accept one like parameter to fill each respective argument ...

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

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
Place code here
{% endraw %}
```

{% include brackets-ide.md %}

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Browser/Source-Browser-Links.htm){:title="Click to Visit the Source Links page of the Browser Lessons Project at GitHub pages"}{:target="_blank"} page of the Browser Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

- [Mastering Javascript High Performance](https://www.packtpub.com/web-development/mastering-javascript-high-performance){:title="Click to Visit the Landing page for Mastering Javascript High Performance by Chad Adams"}{:target="_blank"} by Chad Adams. Published © 2015 by [PACKTpub.com](https://www.packtpub.com/){:title="Click to Visit the Home page of PACKT Publishing"}{:target="_blank"}.
