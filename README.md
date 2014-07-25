SVG-Snippets
============

Type the snippet shortcode and then press `Tab` to complete the snippet.

The snippets are listed below in alphabetical order. The `'$1'` indicates the position of the caret/s. Some snippets have been set up so that pressing Tab jumps the caret/s to the next predefined spot. It's a little hard to explain, but any snippet that has a `$1/$2/$3/etc. uses this technique.

[DEMO-VIMEO](https://vimeo.com/101490820)


###circle

```html
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
```

###circle3

```html
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
<circle r="$1" cx="$2" cy="$3" fill="$4" stroke="$5" stroke-width="$6"/>
```

###circleu

```html
<defs>
	<circle id="$1" r="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
</defs>

<use xlink:href="#$8"/>
<use xlink:href="#$8" x="$9" y="$10"/>
```

###clippath

```html
<defs>
	<clipPath id="$1">
		$2
	</clipPath>
</defs>
```

###defsuse

```html
<defs>

</defs>

<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

###ellipse

```html
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

###ellipse3

```html
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<ellipse rx="$1" ry="$2" cx="$3" cy="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

###ellipseu

```html
<defs>
	<ellipse id="$1" rx="$2" ry="$3" cx="$4" cy="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9" />
<use xlink:href="#$9" x="$10" y="$11"/>
```

###group

```html
<g id="$1">

	$2

</g>
```

###line

```html
<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
```

###lineu

```html
<defs>
	<line x1="$1" y1="$2" x2="$3" y2="$4" stroke="$5" stroke-width="$6"/>
</defs>

<use xlink:href="#$7" />
<use xlink:href="#$7" x="$8" y="$9"/>
```

###lineargradient

```html
<linearGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</linearGradient>
```

###matrix

```html
transform="matrix($1 $2 $3 $4 $5 $6)"
```

###path

```html
<path d="$1" stroke-width="$2" stroke="$3" fill="$4"/>
```

###pattern

```html
<defs>
	<pattern id="$1" width="$2" height="$3" patternUnits="userSpaceOnUse">
		$4
	</pattern>
</defs>
```

###polygon

```html
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

###polygon3

```html
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

###polygonu

```html
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polygon points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

###polyline

```html
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

###polyline3

```html
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
<polyline points="$1" fill="$2" stroke="$3" stroke-width="$4"/>
```

###polylineu

```html
<defs>
	<polyline id="$1" points="$2" fill="$3" stroke="$4" stroke-width="$5"/>
</defs>

<use xlink:href="#$6"/>
<use xlink:href="#$6" x="$7" y="$8"/>
```

###radialgradient

```html
<radialGradient id="$1" gradientUnits="objectBoundingBox">
	<stop offset="$2" stop-color="$3"/>
	<stop offset="$4" stop-color="$5"/>
</radialGradient>
```

###rect

```html
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

###rect3

```html
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
<rect x="$1" y="$2" width="$3" height="$4" fill="$5" stroke="$6" stroke-width="$7"/>
```

###rectu

```html
<defs>
	<rect id="$1" x="$2" y="$3" width="$4" height="$5" fill="$6" stroke="$7" stroke-width="$8"/>
</defs>

<use xlink:href="#$9"/>
<use xlink:href="#$9" x="$10" y="$11"/>
```

###rotate

```html
transform="rotate($1)"
```

###scalable

```html
<svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg"
			viewBox="$1" width="$2" height="$3" aria-labelledby="title desc">

				<title id="title">$4</title>
                <desc id="desc">$5</desc>

</svg>
```

###scalableu

```html
<svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg"
			viewBox="$1" width="$2" height="$3" aria-labelledby="title desc">

				<title id="title">$4</title>
                <desc id="desc">$5</desc>

                <defs>



                </defs>


                <use xlink:href="#" x="" y=""/>

</svg>
```


###skewX

```html
transform="skewX($1)"
```

###skewY

```html
transform="skewY($1)"
```

###symbol

```html
<symbol id="$1">

</symbol>
<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
```

###text

```html
<text x="$1" y="$2" fill="$3">$4</text>
```

###translate

```html
transform="translate($1)"
```

###tspan

```html
<tspan fill="$1" x="$2" y="$3">$4</tspan>
```

###use

```html
<use xlink:href="#$1" x="$2" y="$3"/>
```

###use3

```html
<use xlink:href="#$1"/>
<use xlink:href="#$1" x="$2" y="$3"/>
<use xlink:href="#$1" x="$4" y="$5"/>
```

