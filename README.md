# javascriptactivity2and3
activity2and3
<!DOCTYPE html>
<html>
<head>
<style>
	<title>Javascript Activity 1 - [YOUR NAME HERE]</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1"		>
<style>
body {
    background-image: url("1.jpg");
    background-repeat: no-repeat;
    background-position:cover;
    margin:0px,0px;
    background-attachment: fixed;
}
</style>



</head>
<body>
<div class="container">
	<div class="row">
		<div class="col-sm-3"></div>
		<div class="col-sm-6">
			<form>
				<div class="form-group">
					<label >Value1</label>
					<input type="text" class="form-control" id="Value1">
				</div>
				<div class="form-group">
					<label>Value2:</label>
					<input type="text" class="form-control" id="Value2">
				</div>
				
				<input type="button" class="btn btn-primary" value="+ Add" onclick="add()" "text" oninvalid="alert('You must fill out the form!');" name="fname" required>
				<input type="button" class="btn btn-primary" value="- Subtract" onclick="subtract()">
				<input type="button" class="btn btn-primary" value="* Multiply" onclick="multiply()">
				<input type="button" class="btn btn-primary" value="/ Divide" onclick="divide()">
				

			</form>
			<h3>The answer is: </h3> <h3 id="answer"></h3>
		</div>
		<div class="col-sm-3">
	</div>
</div>
<script type="text/javascript">

function add()
{
var Value1=document.getElementById('Value1').value;
var Value2=document.getElementById('Value2').value;
Value1= Number(Value1);
Value2= Number(Value2);
var total=Value1+Value2;  
document.getElementById('answer').innerHTML=total;

if(isNaN(Value1)==false&&isNaN(Value2)==false)
{
	document.getElementById('answer').innerHTML=total;
	var total=Value1+Value2;
	alert ("The answer is"+sum)
}
else
{
	document.getElementById('answer').innerHTML="DILI PWEDE SIR KASABOT!!!";
	alert("it is not a number")
}
}

function subtract()
{
var Value1=document.getElementById('Value1').value;
var Value2=document.getElementById('Value2').value;
Value1= Number(Value1);
Value2= Number(Value2);
var total=Value1-Value2;
document.getElementById('answer').innerHTML=total;

if(isNaN(Value1)==false&&isNaN(Value2)==false)
{
	document.getElementById('answer').innerHTML=total;
	var total=Value1-Value2;
	alert ("The answer is"-difference)
}
else
{
	document.getElementById('answer').innerHTML="DILI PWEDE SIR KASABOT!!!";
	alert("it is not a number")
}

}
function multiply()
{
var Value1=document.getElementById('Value1').value;
var Value2=document.getElementById('Value2').value;
Value1= Number(Value1);
Value2= Number(Value2);
var total=Value1*Value2;
document.getElementById('answer').innerHTML=total;

if(isNaN(Value1)==false&&isNaN(Value2)==false)
{
	document.getElementById('answer').innerHTML=total;
	var total=Value1*Value2;
	alert ("The answer is"*product)
}
else
{
	document.getElementById('answer').innerHTML="DILI PWEDE SIR KASABOT!!!";
	alert("it is not a number")
}

}
function divide()
{
var Value1=document.getElementById('Value1').value;
var Value2=document.getElementById('Value2').value;
Value1= Number(Value1);
Value2= Number(Value2);
var total=Value1/Value2;
document.getElementById('answer').innerHTML=total;

if(isNaN(Value1)==false&&isNaN(Value2)==false)
{
	document.getElementById('answer').innerHTML=total;
	var total=Value1/Value2;
	alert ("The answer is"/quotient)
}
else
{
	document.getElementById('answer').innerHTML="DILI PWEDE SIR KASABOT!!!";
	alert("it is not a number")
}
}

    
</script>
</body>
</html>
