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

###Defs + use

Write ```defsuse```

```html

/* before */

<defs>

</defs>

<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

##Ellipse

Write ```ellipse```

```html

/* before */

<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

Write ```ellipse3```

```html

/* before */

<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

Write ```ellipseu```

```html

/* before */

<defs>
	<ellipse id="$1" rx="$2" ry="$3" cx="$4" cy="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9" />
<use xlink:href="#$9" x="$10" y="$11"/>
```

##Group

Write ```group```

```html

/* before */

<g id="$1">

	$2

</g>
```

##Line

Write ```line```

```html

/* before */

<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
```

Write ```lineu```

```html

/* before */

<defs>
	<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
</defs>

<use xlink:href="#$7" />
<use xlink:href="#$7" x="$8" y="$9"/>
```

##Lineargradient

Write ```lineargradient```

```html

/* before */

<linearGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</linearGradient>
```

##Matrix

Write ```matrix```

```html

/* before */

transform="matrix($1 $2 $3 $4 $5 $6)"
```

##Path

Write ```path```

```html

/* before */

<path d="$1" stroke-width="$2" stroke="$3" fill="$4"/>
```

##Pattern

Write ```pattern```

```html

/* before */

<defs>
	<pattern id="$1" width="$2" height="$3" patternUnits="userSpaceOnUse">
		$4
	</pattern>
</defs>
```

##Polygon

Write ```polygon```

```html

/* before */

<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```polygon3```

```html

/* before */

<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```polygonu```

```html

/* before */

<defs>
	<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
</defs>

<use xlink:href="#$7" />
<use xlink:href="#$7" x="$8" y="$9"/>
```

##Polyline

Write ```polyline```

```html

/* before */

<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```polyline3```

```html

/* before */

<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

Write ```polylineu```

```html

/* before */

<defs>
	<polyline id="$1" points="$2" fill="$3" stroke="$4" stroke-width="$5"/>
</defs>

<use xlink:href="#$6"/>
<use xlink:href="#$6" x="$7" y="$8"/>
```

##Radialgradient

Write ```radialgradient```

```html

/* before */

<radialGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</radialGradient>
```

##Rect

Write ```rect```

```html

/* before */

<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

##Rect3

Write ```rect3```

```html

/* before */

<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

##Rectu

Write ```rectu```

```html

/* before */

<defs>
	<rect id="$1" x="$2" y="$3" width="$4" height="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9"/>
<use xlink:href="#$9" x="$10" y="$11"/>
```

##Rotate

Write ```rotate```

```html

/* before */

transform="rotate($1)"
```

##Scalable

Write ```scalable```

```html

/* before */

<svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg"
			viewBox="$1" width="$2" height="$3" aria-labelledby="title desc">

				<title id="title">$4</title>
                <desc id="desc">$5</desc>

</svg>
```

##Scalableu

Write ```scalableu```

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

Write ```skewx```

```html

/* before */

transform="skewX($1)"
```

##SkewY

Write ```skewy```

```html

/* before */

transform="skewY($1)"
```

##Symbol

Write ```symbol```

```html

/* before */

<symbol id="$1">

</symbol>
<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

##Text

Write ```text```

```html

/* before */

<text x="$1" y="$2" fill="$3">$4</text>
```

##Translate

Write ```translate```

```html

/* before */

transform="translate($1)"
```

##Tspan

Write ```tspan```

```html

/* before */

<tspan fill="$1" x="$2" y="$3">$4</tspan>
```

##Use

Write ```use```

```html

/* before */

<use xlink:href="#$1" x="$2" y="$3"/>
```

##Use3

Write ```use3```

```html

/* before */

<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
<use xlink:href="#$1" x="$4" y="$5"/>
```

