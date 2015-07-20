## Skeleton Tabs

Tab navigation for Skeleton. [Demo](http://nathancahill.github.io/skeleton-tabs/)

![](http://i.imgur.com/ekJwhya.png)

### Usage

Include `skeleton-tabs.css` and `skeleton-tabs.js` in your HTML:

```
<link rel="stylesheet" href="skeleton-tabs.css">
```

```
<script src="skeleton-tabs.js"></script>
```

Set up the HTML markup for the tab navigation:


```
<ul class="tab-nav">
  <li>
    <a class="button active" href="#one">Tab 1</a>
  </li>
  <li>
    <a class="button" href="#two">Tab 2</a>
  </li>
  <li>
    <a class="button" href="#three">Tab 3</a>
  </li>
</ul>
```

And the HTML markup for tab content:

```
<div class="tab-content">
  <div class="tab-pane active" id="one">...</div>
  <div class="tab-pane" id="two">...</div>
  <div class="tab-pane" id="three">...</div>
</div>
```