## HTML Links

```html
<!-- with anchor thag -->
<a href="https://www.abhishekdipu.tech/" target="_blank" title="abhi's website"
  >Abhishek
</a>

<!-- Link to an Email Address -->
<a href="mailto:abhishekdipu20@gmail.com">Send email</a>

<!-- Button as a Link -->
<button onclick="document.location='default.asp'">HTML Tutorial</button>

<!-- Bookmarks : 2 steps:-->
<h2 id="C4">Chapter 4</h2>
<a href="#C4">Jump to Chapter 4</a>

<!-- 
target attribute: where to open when link is clicked.
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
_self - Default. Opens the document in the same window/tab as it was clicked

title attribute: to display something when mouse hover it.
 -->

<!-- Absolute URLs vs. Relative URLs -->
<!--Absolute URLs   -->
<p><a href="https://www.google.com/">Google</a></p>
<!-- Relative URLs  -->
<p><a href="html_images.asp">HTML Images</a></p>
```

## we can also override the default style behaviour of link

```html
<style>
  a:link {
    color: green;
    background-color: transparent;
    text-decoration: none;
  }

  a:visited {
    color: pink;
    background-color: transparent;
    text-decoration: none;
  }

  a:hover {
    color: red;
    background-color: transparent;
    text-decoration: underline;
  }

  a:active {
    color: yellow;
    background-color: transparent;
    text-decoration: underline;
  }
</style>
```
