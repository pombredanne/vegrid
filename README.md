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

	#TODO, until then check the example folder and it's content.

## Requirements:

	#TODO

## Credits:

* Chris Coyier for inspiring me with his podcast
* The SASS team & community