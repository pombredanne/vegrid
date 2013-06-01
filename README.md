# Fluid Sassy - Grid System

## A CSS grid system by Adonis K. using SASS

## How to use:

__load the grid system__:

```scss
@import "../lib/_grid";
```

__create class units for 4 columns__:

```scss
@include col(4);
```

__this results in__:

```css
.col-1-4 {
	width: 25%;
}

.col-2-4 {
	width: 50%;
}

.col-3-4 {
	width: 75%;
}
```

__which you can later use as following__:

```html
<div class="grid">
	<div class="col-1-4">
		<h1>Column 1/4</h1>
	</div>
	<div class="col-1-4">
		<h1>Column 1/4</h1>
	</div>
	<div class="col-1-4">
		<h1>Column 1/4</h1>
	</div>
	<div class="col-1-4">
		<h1>Column 1/4</h1>
	</div>
</div>

<div class="grid">
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

<div class="grid">
	<div class="col-1-4">
		<h1>Column 1/4</h1>
	</div>
	<div class="col-3-4">
		<h1>Column 3/4</h1>
	</div>
</div>
```


	#TODO, add more examples and easier to understand explanations

## Requirements:

	#TODO

## Credits:

* Chris Coyier for inspiring me with his podcast
* The SASS team & community