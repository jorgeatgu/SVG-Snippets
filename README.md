SVG-Snippets
============

Type the snippet shortcode and then press `Tab` to complete the snippet.

The snippets are listed below in alphabetical order. The `'$1'` indicates the position of the caret/s. Some snippets have been set up so that pressing Tab jumps the caret/s to the next predefined spot. It's a little hard to explain, but any snippet that has a `$1/$2/$3/etc. uses this technique.

#[Package Control](https://packagecontrol.io/packages/SVG-Snippets)
#[CodePen](http://codepen.io/jorgeatgu/blog/svg-snippets)
[![Video Vimeo](https://github.com/jorgeatgu/SVG-Snippets/blob/master/vimeo-image.png)](https://vimeo.com/101490820)

##Circle

Write ```circle```

```html
/* before */

<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
```

Write ```circle3```

```html

/* before */

<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
```

Write ```circleu```

```html

/* before */

<defs>
	<circle id="$1" r="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
</defs>

<use xlink:href="#$8"/>
<use xlink:href="#$8" x="$9" y="$10"/>
```

##Clippath

Write ```clippath```

```html

/* before */

<defs>
	<clipPath id="$1">
		$2
	</clipPath>
</defs>
```

###defsuse

Write ```defsuse```

```html

/* before */

<defs>

</defs>

<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

###ellipse

Write ```defsuse```

```html

/* before */

<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

Write ```defsuse```

```html

/* before */

<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

Write ```defsuse```

```html

/* before */

<defs>
	<ellipse id="$1" rx="$2" ry="$3" cx="$4" cy="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9" />
<use xlink:href="#$9" x="$10" y="$11"/>
```

###group

Write ```defsuse```

```html

/* before */

<g id="$1">

	$2

</g>
```

##Line

Write ```defsuse```

```html

/* before */

<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
```

##Lineu

Write ```defsuse```

```html

/* before */

<defs>
	<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
</defs>

<use xlink:href="#$7" />
<use xlink:href="#$7" x="$8" y="$9"/>
```

##Lineargradient

Write ```defsuse```

```html

/* before */

<linearGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</linearGradient>
```

##Matrix

Write ```defsuse```

```html

/* before */

transform="matrix($1 $2 $3 $4 $5 $6)"
```

##Path

Write ```defsuse```

```html

/* before */

<path d="$1" stroke-width="$2" stroke="$3" fill="$4"/>
```

##Pattern

Write ```defsuse```

```html

/* before */

<defs>
	<pattern id="$1" width="$2" height="$3" patternUnits="userSpaceOnUse">
		$4
	</pattern>
</defs>
```

##Polygon

Write ```defsuse```

```html

/* before */

<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```defsuse```

```html

/* before */

<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```defsuse```

```html

/* before */

<defs>
	<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
</defs>

<use xlink:href="#$7" />
<use xlink:href="#$7" x="$8" y="$9"/>
```

##Polyline

Write ```defsuse```

```html

/* before */

<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```defsuse```

```html

/* before */

<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```defsuse```

```html

/* before */

<defs>
	<polyline id="$1" points="$2" fill="$3" stroke="$4" stroke-width="$5"/>
</defs>

<use xlink:href="#$6"/>
<use xlink:href="#$6" x="$7" y="$8"/>
```

##Radialgradient

Write ```defsuse```

```html

/* before */

<radialGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</radialGradient>
```

##Rect

Write ```defsuse```

```html

/* before */

<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

##Rect3

Write ```defsuse```

```html

/* before */

<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

##Rectu

Write ```defsuse```

```html

/* before */

<defs>
	<rect id="$1" x="$2" y="$3" width="$4" height="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9"/>
<use xlink:href="#$9" x="$10" y="$11"/>
```

##Rotate

Write ```defsuse```

```html

/* before */

transform="rotate($1)"
```

##Scalable

Write ```defsuse```

```html

/* before */

<svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg"
			viewBox="$1" width="$2" height="$3" aria-labelledby="title desc">

				<title id="title">$4</title>
                <desc id="desc">$5</desc>

</svg>
```

##Scalableu

Write ```defsuse```

```html

/* before */

<svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg"
			viewBox="$1" width="$2" height="$3" aria-labelledby="title desc">

				<title id="title">$4</title>
                <desc id="desc">$5</desc>

                <defs>



                </defs>


                <use xlink:href="#" x="" y=""/>

</svg>
```


##SkewX

Write ```defsuse```

```html

/* before */

transform="skewX($1)"
```

##SkewY

Write ```defsuse```

```html

/* before */

transform="skewY($1)"
```

##Symbol

Write ```defsuse```

```html

/* before */

<symbol id="$1">

</symbol>
<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

##Text

Write ```defsuse```

```html

/* before */

<text x="$1" y="$2" fill="$3">$4</text>
```

##Translate

Write ```defsuse```

```html

/* before */

transform="translate($1)"
```

##Tspan

Write ```defsuse```

```html

/* before */

<tspan fill="$1" x="$2" y="$3">$4</tspan>
```

##Use

Write ```defsuse```

```html

/* before */

<use xlink:href="#$1" x="$2" y="$3"/>
```

##Use3

Write ```defsuse```

```html

/* before */

<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
<use xlink:href="#$1" x="$4" y="$5"/>
```

