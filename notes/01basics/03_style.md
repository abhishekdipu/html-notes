- The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

```html
<!-- syntax  -->
<tagname style="property:value;"></tagname>

<!-- color related styles -->
<!-- 1. Background Color -->
<body style="background-color:powderblue;"></body>

<!-- 2.Text Color -->
<h1 style="color:blue;">This is a heading</h1>

<!-- 3. Border Color -->
<h1 style="border:2px solid Tomato;">Hello World</h1>

<!-- 3.Fonts -->
<h1 style="font-family:verdana;">This is a heading</h1>

<!-- 4. Text Size -->
<h1 style="font-size:300%;">This is a heading</h1>

<!-- 5.Text Alignment -->
<h1 style="text-align:center;">Centered Heading</h1>
```

## colors:

1. HTML colors are specified with predefined color names. eg. red, green, blue, tomato, tan etc
2. or with
   - RGB, RGBA
   - HEX,
   - HSL, HSLA

### 1 . RGB (red, green, blue) : rgb(255, 0, 0)

- Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255.
- This means that there are 256 x 256 x 256 = 16777216 possible colors!
- black: rgb(0, 0, 0).
- white: rgb(255, 255, 255).
- red: rgb(255, 0, 0)

```html
<h1 style="background-color:rgb(255, 0, 0);">red color</h1>
```

### 1.1. RGBA rgba(red, green, blue, alpha) : rgba(255, 0, 0, 0.5)

- The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):

```html
<h1 style="background-color:rgba(255, 99, 71, 0.5);">half transparent</h1>
```

### 2. HEX (#RRGGBB): ff0000

- A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers, hexadecimal values between 00 and ff (same as decimal 0-255)
- black: #000000
- white: #ffffff
- red: #ff0000

### 3. HSL (hue, saturation, lightness) : hsl(0, 100%, 50%)

- Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
- Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.
- Lightness is also a percentage value, 0% is black, and 100% is white.

- black: hsl(any, any%, 0%)
- white: hsl(any, any%, 100%)
- red: hsl(0, 100%, 50%)

```html
<h1 style="background-color:hsl(0, 100%, 50%);">red color</h1>
```

### 3.2 hsla(hue, saturation, lightness, alpha):

```html
<h1 style="background-color:hsla(0, 100%, 50%, 0.5);">red half tranparent</h1>
```
