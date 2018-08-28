---
layout: default
---


# Header 1
Hello There

{{ site.style }}

<p> the style :{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}
 </p>

<p> the print : {{ '/assets/css/print.css' | relative_url }} </p>


<p> rel url : {{ relative_url }}

<p> abs url : {{ absolute_url }}

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
