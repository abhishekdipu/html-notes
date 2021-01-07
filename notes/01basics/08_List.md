## HTML Lists

### Ordered HTML List

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ol type="1">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<!-- 
type="1" :-	The list items will be numbered with numbers (default)
type="A" :-	The list items will be numbered with uppercase letters
type="a" :-	The list items will be numbered with lowercase letters
type="I" :- The list items will be numbered with uppercase roman numbers
type="i" :-	The list items will be numbered with lowercase roman numbers
-->
```

### Unordered HTML List

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<!-- Unordered HTML List - Choose List Item Marker -->
<ul style="list-style-type:disc;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<!-- 
disc   : Sets the list item marker to a bullet (default)
circle : Sets the list item marker to a circle
square : Sets the list item marker to a square
none   : The list items will not be marked
 -->
```

### HTML Other Lists

```html
<!-- HTML Description Lists -->
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

<!-- 
<dl> element to define a description list
<dt> element to define the description term
<dd> element to describe the term in a description list
 -->
```
