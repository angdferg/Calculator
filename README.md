<h1>This calculator is meant to add only two numbers together. After both number have been entered,<br>the answer will appear below :) </h1>
<html lang="en">

<head>


<meta charset="utf-8">
</head>


<body>

<h2>  The answer is: </h2>
<p id="answer"> </p> 

<main>
<script>
var  num1 = Number( prompt("Enter your first number: "));
var  num2 = Number (prompt("Enter another numer: "));
var sum= num1 +num2;
document.getElementById ('answer').innerHTML=sum;
</script>
</main>

<footer>
  <h6>Created for Working with Programming Assignment</h6>
</footer>

</body>

</html>
