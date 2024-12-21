<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="1.js">
    <title>User Login and Registration</title>
    
</head>
<body>

<div class="container" id="loginContainer">
    <h2>Login</h2>
    <input type="text" id="loginUsername" placeholder="Username">
    <input type="password" id="loginPassword" placeholder="Password">
    <button onclick="login()">Login</button>
    <p class="message" id="loginMessage"></p>
    <p>Don't have an account? <a href="#" onclick="showRegister()">Register here</a>.</p>
</div>

<div class="container" id="registerContainer" style="display: none;">
    <h2>Register</h2>
    <input type="text" id="registerUsername" placeholder="Username">
    <input type="password" id="registerPassword" placeholder="Password">
    <button onclick="register()">Register</button>
    <p class="message" id="registerMessage"></p>
    <p>Already have an account? <a href="#" onclick="showLogin()">Login here</a>.</p>
</div>


</div>



</body>
</html>
