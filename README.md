<!DOCTYPE HTML>
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        .playbook-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-image: url('background.jpg'); /* Replace with your photography */
            background-size: cover;
            background-position: center;
        }

        .playbook-form {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            padding: 40px;
            width: 320px;
            text-align: center;
        }

        .logo {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background-color: #e74c3c; /* Red color */
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 auto 20px;
            font-size: 36px;
            color: #ffffff;
        }

        .input-field {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .login-button {
            background-color: #e74c3c; /* Red color */
            color: #ffffff;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }

        .login-button:hover {
            background-color: #c0392b; /* Darker shade of red */
        }

        .forgot-password {
            margin-top: 15px;
            font-size: 14px;
            color: #555555;
        }
    </style>
    <title>Playbook Login Page</title>
</head>
<body>
    <div class="playbook-container">
        <div class="playbook-form">
            <div class="logo">P</div>
            <input type="text" class="input-field" placeholder="Username">
            <input type="password" class="input-field" placeholder="Password">
            <button class="login-button">Log In</button>
            <div class="forgot-password">Forgot your password?</div>
        </div>
    </div>
</body>
</html>
