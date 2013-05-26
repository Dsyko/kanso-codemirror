kanso-codemirror
================

Codemirror wrapped in a kanso package

Using the package
-----

Add the `Codemirror` .js and .css assets to your html files, in this example I've included the monokai theme

```html
<script src="lib/codemirror.js"></script>
<link rel="stylesheet" type="text/css" href="lib/codemirror.css">
<link rel="stylesheet" type="text/css" href="theme/monokai.css">
<script src="mode/python/python.js"></script>
```
Create a div or textarea to hold the Codemirror:

```html
<textarea id="Codemirror" class="your styles here"></textarea>
```

Instantiate Codemirror on the div or textarea per the user manual:

```javascript
var myCodeMirror = CodeMirror.fromTextArea($("#Codemirror")[0], {theme: "monokai"});
```


You're done! See [Codemirror](http://codemirror.net/) for more.
All the assets from Codemirror 3.13 are attached by this module
