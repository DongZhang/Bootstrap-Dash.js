Bootstrap-trunk-js
==================

A nice and fully-featured responsive system provide two kind of navigation menu.
JQuery and Bootstrap are needed.

##Basic usage
include the following stylesheets in header
```
<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
<link rel="stylesheet" type="text/css" href="css/font-awesome.css">
<link rel="stylesheet" type="text/css" href="css/dash.css">
```
include the following js files
```
<script src="js/jquery-1.10.1.js"></script>
<script src="js/bootstrap.js"></script>
<script src="js/dash.js"></script>
```

###nav-auto
```
<header>
  <h1>Your header</h1>
  <ul class="burger" id="navtoggle-auto">
    <li></li><li></li><li></li>
  </ul>
</header>
<nav class="nav-auto">
  Your nav menu
</nav>
<div class="content-auto">
  Your content
</div>
```
###nav-fixed
```
<header>
  <h1>Your header</h1>
  <ul class="burger visible-sm visible-xs" id="navtoggle-fixed">
    <li></li><li></li><li></li>
  </ul>
</header>
<nav class="nav-fixed">
  Your nav menu
</nav>
<div class="content-fixed">
  Your content
</div>
```
