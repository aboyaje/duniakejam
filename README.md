
<!DOCTYPE html>
<html>
<head>
	<title>tes tis</title>
	<meta charset="utf-8">
</head>
<body>

<form id="formboy">
	<input type="text" name="Username" id="username">
	<input type="password" name=""
	 id="password">
	<button id="btnsubmit" type="submit">submit</button> 

</form>

<script type="text/javascript">
	var username = document.getElementById('username');
	var password = document.getElementById('password');
	var btnSubmit = document.getElementById('btnsubmit');
	var formBoy = document.getElementById('formboy');


	// btnSubmit.onclick = formValid;
	formBoy.onsubmit = formValid;


	function formValid(){
		if(username.value == '' || username.value.length < 5){
			alert('Username Salah');
		}else if(password.value == '' || password.value.length < 5){
			alert('password salah');
		}else{
			alert('username ga salah');
		}
	}
</script>



</body>
</html>


alert("tes");
