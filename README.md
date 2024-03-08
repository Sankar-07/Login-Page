//html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>
<link rel="stylesheet" href="styles.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>

<div class="login-container">
    <i class="fas fa-lock"></i>
    <h2>Login</h2>
    <form>
        <input type="text" placeholder="Username" required><br>
        <input type="password" placeholder="Password" required><br>
        <input type="submit" value="Login">
    </form>
    <div class="footer">
        Don't have an account? <a href="#">Sign up</a>
    </div>
</div>

</body>
</html>




//css


body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
}

.login-container {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.1);
    width: 320px;
    margin: 100px auto;
    padding: 40px 30px;
    text-align: center;
    transition: all 0.3s ease;
}

h2 {
    color: #333;
    margin-bottom: 30px;
}

input[type="text"], input[type="password"] {
    width: calc(100% - 20px);
    padding: 12px;
    margin: 10px 0;
    border: none;
    border-bottom: 1px solid #ddd;
    background-color: transparent;
    transition: all 0.3s ease;
}

input[type="text"]:focus, input[type="password"]:focus {
    border-bottom: 1px solid #6c63ff;
    outline: none;
}

input[type="submit"] {
    width: 100%;
    background-color: #6c63ff;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: all 0.3s ease;
}

input[type="submit"]:hover {
    background-color: #5248ff;
}

.footer {
    margin-top: 20px;
    color: #666;
    font-size: 14px;
}

.footer a {
    color: #333;
    text-decoration: none;
}

.footer a:hover {
    text-decoration: underline;
}

.fa-lock {
    font-size: 50px;
    color: #6c63ff;
    margin-bottom: 20px;
}
