Tooltip
-------
_A simple reusable tooltip jquery component_

#### Demo
[https://leomanlapera.github.io/tooltip/](https://leomanlapera.github.io/tooltip/)

#### Setup
Just add a link to the css file in your `<head>`

```html
<link rel="stylesheet" type="text/css" href="css/tooltip.css">
```

Then, add before your closing ```<body>``` tag

```html
<script type="text/javascript" src="js/jquery.tooltip.js"></script>
```

#### Example usage

Default tooltip

```html
<span class="tooltip" data-content="Your tooltip content goes here...">default tooltip</span>
```

jQuery code
```javascript
$('.tooltip').tooltip();
```

#### Options

Right position
```javascript
$('.tooltip').tooltip({
	position: 'right'
});
```

Left position
```javascript
$('.tooltip').tooltip({
	position: 'left'
});
```

Bottom position
```javascript
$('.tooltip').tooltip({
	position: 'bottom'
});
```

Changing the label color
```javascript
$('.tooltip').tooltip({
	labelColor: '#673AB7'
});
```

Changing the content background color
```javascript
$('.tooltip').tooltip({
	contentBGColor: '#4CAF50'
});
```

#### Browser support
Modern browser :D

#### Dependencies
jQuery 1.7

#### Licence
Copyright 2016 June Leoman Lapera
Licenced under MIT license.

Have fun!