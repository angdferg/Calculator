<h1>Adding Calculator</h1>
<html lang="en">

<head>


<meta charset="utf-8">
</head>


<body>

<h1>  The answer is: </h1>
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
</footer>

</body>

</html>
