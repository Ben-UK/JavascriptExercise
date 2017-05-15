# JavascriptExercise
JavascriptExercise
<!DOCTYPE html>
<html lang="en">
<head>
</head>

<body ()>

<script>

function squareNumber(square)
{

return square*square;

}
squareNumber();
</script>

<form name='SquareNumber'> 
<input type=text name="input">
<input type=button value="enter a number to find it's square" onclick='document.write("Square is: " +
		squareNumber(SquareNumber.input.value));'>
  
</form>

<script>

function sumOf3Numbers(input1,input2,input3)
{
var input1 = Number(input1);
var input2 = Number(input2);
var input3 = Number(input3);

return input1+input2+input3;

}
sumOf3Numbers();
</script>

<form name='sumOf3Numbers1'> 
<input type=text name="input1">
<input type=text name="input2">
<input type=text name="input3">
<input type=button value="Enter 3 numbers to find the sum of the 3" onclick='document.write("The sum of 3 numbers is: " +
		sumOf3Numbers(sumOf3Numbers1.input1.value,sumOf3Numbers1.input2.value,sumOf3Numbers1.input3.value));'>
  
</form>

<script>
function person(input4,input5,input)
{
var input4 = Number(input4);
var input5 = Number(input5);
var input6 = Number(input6);

return input4,input5,input6;

}
person();
</script>

<form name='PersonForm'> 
<input type=text value="name" name="input4">
<input type=text value="age" name="input5">
<input type=text value="occupation" name="input6">
<input type=button value="Enter person details" onclick='document.write("The persons details are: Name:" + person(PersonForm.input4.value + "age; " + PersonForm.input5.value + "occupation" + PersonForm.input6.value));'>
  
</form>

<script>

var variableObject ={
	name:"He said \"My name is elliott\""
};

window.alert(variableObject.name.toUpperCase());
</script>

<p id="stringTest"></p>
<p id="stringTestNumbers"></p>

<script>



var result = "1" + 5;

document.getElementById("stringTest").innerHTML = result;


</script>


</body>
</html>
