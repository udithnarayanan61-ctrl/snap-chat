# snap-chat
<!DOCTYPE html>
<html>
<head>
    <title>Snapchat Login</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #fffc00;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-box {
            background: white;
            width: 350px;
            padding: 40px;
            border-radius: 15px;
            text-align: center;
        }

        h1 {
            color: #000;
        }

        input {
            width: 90%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            width: 97%;
            padding: 12px;
            background: #fffc00;
            border: 2px solid black;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #eee900;
        }
    </style>
</head>

<body>

<div class="login-box">
    <h1>👻 Snapchat</h1>

    <input type="text" placeholder="Username or Email">
    <br>

    <input type="password" placeholder="Password">
    <br><br>

    <button onclick="login()">Log In</button>

    <p id="message"></p>
</div>

<script>
    function login() {
        document.getElementById("message").innerHTML =
            "Login button clicked!";
    }
</script>

</body>
</html>
