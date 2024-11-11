### JavaScript Where To
#### The ``<script>`` Tag
In HTML, JavaScript code is inserted between <script> and </script> tags.
```
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

#### JavaScript in ``<head>`` or ``<body>``
You can place any number of scripts in an HTML document.

Scripts can be placed in the ``<body>``, or in the ``<head>`` section of an HTML page, or in both.

```
<!DOCTYPE html>
<html>
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
<body>
<h2>Demo JavaScript in Head</h2>

<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

</body>
</html>
```