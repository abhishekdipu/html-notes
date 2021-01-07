# HTML class Attribute

- To create a class; write a period (.) character, followed by a class name. Then, define the CSS properties within curly braces {}:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .city {
        background-color: tomato;
        color: white;
      }
      .state {
        background-color: blue;
        color: white;
        padding: 10px;
      }
    </style>
  </head>

  <body>
    <div class="city">
      <h2>London</h2>
    </div>

    <div class="city state">
      <h2>Dhanbad</h2>
    </div>
  </body>
</html>
```

## Note:

- Tip: The class attribute can be used on any HTML element.

- The class name is case sensitive!

# Use of The class Attribute in JavaScript

```html
<!-- Click on a button to hide all elements with the class name "city": -->

<!DOCTYPE html>
<html>
  <body>
    <h2>Use of The class Attribute in JavaScript</h2>
    <p>Click the button to hide all elements with class name "city":</p>

    <button onclick="myFunction()">Hide elements</button>

    <h2 class="city">London</h2>
    <p>London is the capital of England.</p>

    <h2 class="city">Paris</h2>
    <p>Paris is the capital of France.</p>

    <h2 class="city">Tokyo</h2>
    <p>Tokyo is the capital of Japan.</p>

    <script>
      function myFunction() {
        var x = document.getElementsByClassName("city");
        for (var i = 0; i < x.length; i++) {
          x[i].style.display = "none";
        }
      }
    </script>
  </body>
</html>
```
