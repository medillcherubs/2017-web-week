# 2017-cherub-timeline
Cherubs through the years timeline and alumni profiles

https://medillcherubs.github.io/2017-web-week/cherub-alumni-timeline/

Paste this into your Wordpress post:

```
[raw]<div id="cherub-timeline"></div>
<script> var pymParent = new pym.Parent("cherub-timeline", "//medillcherubs.github.io/2017-web-week/cherub-alumni-timeline/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2017-web-week/edit/master/cherub-alumni-timeline/index.html -->
[/raw]
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
