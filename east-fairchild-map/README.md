## 2017-east-fairchild-map
#### [INSERT Names of project producers]

[INSERT Description of what this project is.]

#### Viewing this project
You can view the project [live on GitHub Pages](https://medillcherubs.github.io/2017-web-week/east-fairchild-map/index.html) and you can see the page where it's been embedded [into the Cherub WordPress site]().

  [UPDATE Link to the published version of this project on WordPress.]

#### Editing the Content
To edit the content in this project you need to edit the HTML in the index.html page. Click on this link to go to the editor. Make the changes you want to make, then click the green "Commit" button at the bottom of the page. You should see the changes appear within a minute on the WordPress site.

#### Embedding In WordPress

Paste this into your WordPress post, under the "Text" tab instead of the "Visual" tab:

```
[raw]
<div id="github-container"></div>
<script> var pymParent = new pym.Parent("github-container", "//medillcherubs.github.io/2017-web-week/east-fairchild-map/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2017-web-week/east-fairchild-map/edit/gh-pages/index.html -->
[/raw]
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/1.3.0/p.v1.m.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script>
```
