<!DOCTYPE html>
<html>
<body>

<h1>My First Page</h1>
<input type="Text" id="txtbox" onChange="myFunction()"/>
<p id="demo"></p>

<script>
function myFunction() {
var text = document.getElementById("txtbox").value
document.getElementById("demo").innerHTML = text;
}
</script>

</body>
</html>
