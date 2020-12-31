## HTML Images

### 1. img tag

```html
<!-- <img> or <img/> -->
<img src="pic_flag.jpg" alt="Indian flag" style="width:500px;height:600px;" />
```

### 2. picture tag

```html
<!-- used when 
1) if you want show diff image for diff screen size.
-->
<picture>
  <source media="(min-width: 650px)" srcset="bigcar.jpg" />
  <source media="(min-width: 465px)" srcset="smallcar.jpg" />
  <img src="myface.jpg" />
</picture>
<!--
2) if you are not sure your brower will support which image format.
-->
<picture>
  <source srcset="car.png" />
  <source srcset="car.jpg" />
  <img src="myface.jpg" />
</picture>
<!-- Note: Always specify an <img> element as the last child element of the <picture> element. The <img> element is used by browsers that do not support the <picture> element, or if none of the <source> tags match. -->
```

### 3. HTML Image Maps

```html
<img
  src="workplace.jpg"
  alt="Workplace"
  width="400"
  height="379"
  usemap="#workmap"
/>
<map name="workmap">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm" />
</map>
```

### 4. HTML Background Images

```html
<div style="background-image: url('img_mine.jpg');">some text</div>
<!-- With css -->
<style>
  body {
    background-image: url("img_girl.jpg");
    /* To avoid the background image from repeating itself */
    background-repeat: no-repeat;
    /* background image to cover the entire element ; If you want the background image to stretch to fit the entire element, you can set the background-size property to 100% 100%:*/
    background-size: cover;
    /* to make sure the entire element is always covered */
    background-attachment: fixed;
  }
</style>
```

## something extra (not imp)

```html
<!-- -->

<!--2. Image Size - Width and Height; 2 ways: 1)html width height attbt 2) css style (preferred) -->
<img src="pic_flag.jpg" alt="Indian flag" width="500" height="600" />
<img src="pic_flag.jpg" alt="Indian flag" style="width:500px;height:600px;" />

<!--3. if we want image and then some text, or some text then a image -->
<p>
  <img
    src="smiley.gif"
    alt="Smiley face"
    style="float:right;width:42px;height:42px;"
  />
  The image will float to the right of the text.
</p>

<p>
  <img
    src="smiley.gif"
    alt="Smiley face"
    style="float:left;width:42px;height:42px;"
  />
  The image will float to the left of the text.
</p>

<!-- Description
1. The <img> tag is empty, it contains attributes only, and does not have a closing tag.
2. The <img> tag has two required attributes:
src - Specifies the path to the image
alt - Specifies an alternate text for the image, when image is not able to load due to some reason
3. The width and height attributes always define the width and height of the image in pixels.

4.Width and Height, or Style ?
ans : style attribute bcz It prevents styles sheets from changing the size of images

## Image Maps
rect - defines a rectangular region
circle - defines a circular region
poly - defines a polygonal region
default - defines the entire region


<area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm" />
290=> from left; 172=> from top; 333=>from left; 250=> from top




//for circle
<area shape="circle" coords="337, 300, 44" href="coffee.htm">
337,300,44 => (center coordinates 337 from left; 300 from top and 44 radius)



-->
```
