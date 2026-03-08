<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Log in to Roblox</title>
    <style>
        body {
            background-color: #eeeeee;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            background: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 380px;
            text-align: center;
        }
        img {
            width: 180px;
            margin-bottom: 30px;
        }
        input {
            width: 100%;
            padding: 14px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
            box-sizing: border-box;
        }
        input:focus {
            border-color: #00a2ff;
            outline: none;
        }
        button {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: none;
            border-radius: 4px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
        }
        .login-btn {
            background: linear-gradient(90deg, #00d1ff, #00a2ff);
            color: white;
        }
        .cancel-btn {
            background: #e0e0e0;
            color: #333;
        }
        a {
            color: #006dcc;
            text-decoration: none;
            font-size: 14px;
        }
        a:hover { text-decoration: underline; }
        .forgot { text-align: right; margin-bottom: 20px; }
        .signup { margin-top: 20px; font-size: 14px; }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://logos-world.net/wp-content/uploads/2022/05/Roblox-Logo.png" alt="Roblox Logo">
        <input type="text" placeholder="Username / Email / Phone">
        <input type="password" placeholder="Password">
        <div class="forgot">
            <a href="#">Forgot password or username?</a>
        </div>
        <button class="login-btn">Log In</button>
        <button class="cancel-btn">Cancel</button>
        <div class="signup">
            <a href="#">Don't have an account? Sign Up</a>
        </div>
    </div>
</body>
</html>
