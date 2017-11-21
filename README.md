# W
ls is  a duli
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style type="text/css">
	.classA{

		font-size: 16pt;
		font-family: arial,helvetica,sans-serif;
		padding: 20px;
		color: green;
		background-color='yellow';
	}
	.classB{

		font-size: 30pt;
		font-family: arial,helvetica,sans-serif;
		padding: 40px;
			color: blue;
		background-color='red';
	}
	</style>
	<script type="text/javascript">
		function toggle(){

			var myElement=document.getElementById('id1');
			if (myElement.className=="classA") {

				myElement.className="classB";
				
			}
			else{
			myElement.className="classA";
			}
		}
		window.onload=function(){
			document.getElementById('btn1').onclick=toggle;
		}
	</script>
</head>
<body>
<div id="id1" class="classA">Welcome back to my site</div>
<input type="button" id="btn1" value="Toggle">
<button></button>
</body>

</html>
