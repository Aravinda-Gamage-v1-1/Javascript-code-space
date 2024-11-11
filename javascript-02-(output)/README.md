### Output
#### JavaScript display possibilities
javascript can "display" data in different ways
* writing into an HTML element, using `innerHTML`
* writing into an HTML output, using `document.write()`
* writing into an alert box, using `window.alert()`
* writing into the browser console, using `console.log()`

#### innerHTML
To access an HTML element, javascript can use the document.getElementById(id) method.
The id attribute defines the HTML element. The innerHTML property defines the HTML content.
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Output</title>
  </head>
  <body>
    <h1>My First Web Page</h1>
    <p>My First Paragraph</p>

    <p id="demo"></p>

    <script>
      document.getElementById("demo").innerHTML = 5 + 6;
    </script>
  </body>
</html>
```
#### document.write()
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
document.write(5 + 6);
</script>

</body>
</html>
```
Using document.write() after an HTML document is loaded, will delete all existing HTML
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<button type="button" onclick="document.write(5 + 6)">Try it</button>

</body>
</html>
```
#### window.alert()
You can use an alert box to display data
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
window.alert(5 + 6);
</script>

</body>
</html>
```
#### console.log()
For debugging purposes, you can call the console.log() method in the browser to display data.
```
<!DOCTYPE html>
<html>
<body>

<script>
console.log(5 + 6);
</script>

</body>
</html>
```
#### JavaScript Print
JavaScript does not have any print object or print methods.
You cannot access output devices from JavaScript.
The only exception is that you can call the window.print() method in the browser to print the content of the current window.
```
<!DOCTYPE html>
<html>
<body>

<button onclick="window.print()">Print this page</button>

</body>
</html>
```
