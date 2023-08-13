<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Assignment 3</title>
<style>
  body {
    font-family: Arial, sans-serif;
  }
  .middle {
    margin: 0 auto;
    border: 1px solid black;
    border-spacing: 1px;
  }
  .center {
    text-align: center;
  }
  .right {
    text-align: right;
  }
  .green {
    background-color: green;
  }
  .blue {
    background-color: blue;
  }
  td {
    padding: 1px;
    border: 1px solid black;
  }
</style>
</head>
<body>
<h1 style="text-align: center;">HTML Assignment #3</h1>

<!-- Table 1 -->
<table class="middle" id="table-1">
  <tr>
    <td class="center">Cell 1-1</td>
    <td class="center">Cell 1-2</td>
    <td class="center right">Cell 1-3</td>
  </tr>
  <tr>
    <td class="center">Cell 2-1</td>
    <td class="center">Cell 2-2</td>
    <td class="center right">Cell 2-3</td>
  </tr>
  <tr>
    <td id="t11" class="center">Cell 3-1</td>
    <td id="t12" class="center">Cell 3-2</td>
    <td id="t13" class="center right">Cell 3-3</td>
  </tr>
</table>

<!-- Table 2 -->
<table class="middle" id="table-2">
  <tr>
    <td id="t21" colspan="6" class="center">Table 2 - Row 1</td>
  </tr>
  <tr>
    <td class="center">Cell 2-1</td>
    <td class="center">Cell 2-2</td>
    <td class="center">Cell 2-3</td>
    <td class="center">Cell 2-4</td>
    <td class="center">Cell 2-5</td>
    <td class="center">Cell 2-6</td>
  </tr>
  <!-- Add more rows if needed -->
</table>

<!-- Table 3 -->
<table class="middle" id="table-3">
  <tr class="green">
    <td colspan="2" class="center">Green Row 1</td>
    <td colspan="2" class="center">Green Row 1</td>
  </tr>
  <tr>
    <td id="t-image" rowspan="2" class="center"><img src="your-image-url.jpg" alt="Image"></td>
    <td class="center">Cell 2-1</td>
    <td class="center">Cell 2-2</td>
  </tr>
  <tr class="blue">
    <td class="center">Cell 3-1</td>
    <td class="center">Cell 3-2</td>
  </tr>
</table>

</body>
</html>
