# Ace plugin for Ractive.js

[See the demo here.](http://dagnelies.github.io/ractive-ace/)

## Usage

Import required scripts:

```html
<!-- Ace -->
<script src='https://cdnjs.cloudflare.com/ajax/libs/ace/1.2.9/ace.js'></script>

<!-- Ractive -->
<script src='https://cdn.jsdelivr.net/npm/ractive'></script>

<!-- this plugin -->
<script src='https://cdn.rawgit.com/dagnelies/ractive-ace/master/src/ractive-ace.js'></script>
```


Then use it in your template as follows:

```html
<ace mode="html" value="{{data.bound.content}}" theme="Monokai" />
```
