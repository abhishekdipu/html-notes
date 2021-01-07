# HTML Iframes

- An HTML iframe is used to display a web page within a web page.

- It is a good practice to always include a title attribute for the iframe. This is used by screen readers to read out what the content of the iframe is.

## Iframe - Remove the Border

- By default, an iframe has a border around it.
  To remove the border, add the style attribute and use the CSS border property:

## Iframe - Target for a Link (if we want to load any website in iframe by clicking on a link)

```html
<!DOCTYPE html>
<html>
  <body>
    <h2>Iframe - Target for a Link</h2>

    <iframe
      src="demo_iframe.htm"
      name="iframe_a"
      height="300px"
      width="100%"
      title="Iframe Example"
    ></iframe>

    <p>
      <a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a>
    </p>

    <p>
      When the target attribute of a link matches the name of an iframe, the
      link will open in the iframe.
    </p>
  </body>
</html>
```
