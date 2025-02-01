<!DOCTYPE html>
<html>
<head>
    <title>Instagram Login Simulation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fafafa;
        }
        .login-box {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
        }
        .login-box img {
            width: 150px;
            margin-bottom: 20px;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #3897f0;
            border: none;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="login-box">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/1200px-Instagram_logo_2016.svg.png" alt="Instagram Logo">
        <form id="phishing-form">
            <input type="text" id="username" name="username" placeholder="Phone number, username, or email"><br>
            <input type="password" id="password" name="password" placeholder="Password"><br>
            <button type="submit">Log In</button>
        </form>
    </div>

    <script>
        document.getElementById('phishing-form').addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent actual form submission
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;
            
            // Storing the data temporarily in localStorage
            localStorage.setItem('username', username);
            localStorage.setItem('password', password);

            console.log("Simulated phishing attempt:");
            console.log("Username:", username);
            console.log("Password:", password);
            
            alert("Your data has been logged locally (open console on desktop browser for review).");
        });
    </script>
</body>
</html>
