# veGrid - Grid System

## About

veGrid is a CSS grid system by [Adonis K.](http://varemenos.com) utilizing the power of SASS (SCSS syntax)

## How to use:

__load the grid system__:

```scss
@import "../lib/_grid";
```

__create the grid you need (for example, a 4 column grid)__:

```scss
@include grid(4);
```

__which you can later use as following__:

```html
<div class="grid">
	<div class="row">
		<div class="col-1-4">
			<h1>Column 1/4</h1>
		</div>
		<div class="col-1-4">
			<h1>Column 1/4</h1>
		</div>
		<div class="col-2-4">
			<h1>Column 2/4</h1>
		</div>
	</div>
</div>
```

	#TODO, add more examples and easier to understand explanations

## Requirements & Support:

	#TODO

## Credits:

* Chris Coyier for inspiring me with his podcast
* The SASS team & community