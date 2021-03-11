# xo2
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<style type="text/css">
	body{
		background-color: #FFFFFF;
		user-select: none;
	}
	.qwe{
		padding: 60px;
		border: 12px;

		color: #ffcc99;
		box-shadow: 2px 2px 2px 2px;
		text-align: center;
	}
	.eww{

	}
</style>
<body>
	<h2>This is the x's pole!</h2>
	<table id="wee" class="eww">
	<tr>
			<td class="qwe"></td>
			<td class="qwe"></td>
			<td class="qwe"></td>
		</tr>
		<tr>
			<td class="qwe"></td>
			<td class="qwe"></td>
			<td class="qwe"></td>
		</tr>
		<tr>
			<td class="qwe"></td>
			<td class="qwe"></td>
			<td class="qwe"></td>
		</tr>
		</table>

<script>
 var wee=document.getElementById('wee');
 var qwe=document.getElementsByClassName('qwe');
 var eww=document.getElementsByClassName('eww');
var player1='o';
var player2='x';

var winIndex=[
[1,2,3],
[4,5,6],
[7,8,9],
[1,4,7],
[2,5,8],
[3,6,9],
[1,5,7],
[3,5,7]
];
for (var i = 0; i <= 9; i++) {
	eww.innerHTML += "table class='eww' pos=" + i +"></table>"
}
for (var i = 0; i < qwe.length; i++) {
	qwe[i].addEventListener('click', qweClick, false);

}
function qweClick(){
	var data=[];
	if(!this.innerHTML){
		this.innerHTML= player2;
	} else{
		alert("Busy!");
		return;
	}
}
 
</script>
		
</body>
</body>
</html>
