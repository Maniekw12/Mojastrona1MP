# Mojastrona1MP
1 MP Strona internetowa M.W
<DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
	<title>zadanie 4 - test</title>
	
</head>
<body>
<script>
function spr(){


var odpa = document.getElementById("odpa").checked;
var odpb = document.getElementById("odpb").checked;
var odpc = document.getElementById("odpc").checked;


console.log(odpa,odpb,odpc);
 if  (odpc == true) odp = "dobrze";
	else odp = ".źle";
	document.getElementById("wynik").innerHTML = "<br>" + odp;
}

</script>

<div id="test">
<h3>ile to jest 2*2+2?</hr>
	<input type="radio" name="wybory" value="A" id="A" id="odpa"> 10<br>
	<input type="radio" name="wybory" value="A" id="B" id="odpb"> 10<br>
	<input type="radio" name="wybory" value="A" id="C" id="odpc"> 10<br>
<br>
<button onclick="spr()">Sprawdź</button>
</div>

</body>

</html>

