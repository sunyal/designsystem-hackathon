#Design System for Hackathons


####HTML Template

[Download](https://github.com/PBGUX/designsystem-hackathon/archive/master.zip) the index.html file from this repo or [copy/paste the raw html](https://raw.githubusercontent.com/PBGUX/designsystem-hackathon/master/index.html) to your file. 

####CDN Links

In the `<head>` of your HTML page, include links to the stylesheets:

```html
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.rawgit.com/PBGUX/designsystem/v2.4.0/dist/css/design_system.css" rel="stylesheet">
```

Right before the closing `</body>` include the required JavaScript files:

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```

####Bower Install

Use [Bower](http://www.bower.io) from a terminal command prompt:

```shell
bower install pb-design-system --save
```
