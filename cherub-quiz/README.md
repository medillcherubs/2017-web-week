## 2017-cherub-quiz
#### [INSERT Names of project producers]

[INSERT Description of what this project is.]

[INSERT Link to the published version of this project on Github.]

Paste this into your Wordpress post, under the "Text" tab instead of the "Visual" tab:

```
[raw]
<div id="github-container"></div>
<script> var pymParent = new pym.Parent("github-container", "//medillcherubs.github.io/2017-web-week/cherub-quiz/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2017-web-week/cherub-quiz/edit/gh-pages/index.html -->
[/raw]
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/1.3.0/p.v1.m.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script>
```
