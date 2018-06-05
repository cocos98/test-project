<!DOCTYPE html>
<html>
<body>
<label>inserisci misura</label>
<input type="number" id="input">
<button id="car" onclick="myFunction1()">Click me</button>
<button onclick="myFunction()">click</button></br></br>
<button onclick="su()" style="margin-left:55px" >su</button></br></br>
<button onclick="sinistra()">sinistra</button>&nbsp&nbsp;&nbsp;&nbsp;&nbsp;
<button onclick="destra()">destra</button></br></br>
<button onclick="giu()" style="margin-left:55px">giu</button>


<p id="demo"></p>
<img src="download.jpg" id="img">

<script>
var grosso=document.img.style.width;
var aumenta= 19;
grosso=200;

function su(){
img.style.margin-top==input;
}
function giu(){

}
function destra(){
img.style.margin-right=input;
}
function sinistra(){

}
function myFunction() {
grosso += aumenta;
img.style.width=grosso.aumenta;

    document.getElementById("demo").innerHTML = "Hello World";
	document.getElementById("car").style.visibility="hidden";
	//document.getElementById("img").style.visibility="hidden";
	document.getElementById("img").margin-left=150px;
}
</script>
</body>
</html>
