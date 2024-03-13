<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">

    <title>Sign Up</title>
</head>
<body>
    <div class="signup-box">
        <h1>Sign Up</h1>
        <h4>Just a few steps and you're good to go</h4>
        <form onsubmit="return validatePassword()">
            <label>First Name</label>
            <input type="text" placeholder="" required>
            <label>Last Name</label>
            <input type="text" placeholder="" required>
            <label>Email</label>
            <input type="email" placeholder="" required>
            <label>Password</label>
            <input type="password" id="password" placeholder="" required>
            <label>Confirm Password</label>
            <input type="password" id="confirmPassword" placeholder="" required>
            <label>College Name</label>
            <input type="text" placeholder="" required>
            <button type="submit" class="btn">Submit</button>
        </form>
        
        <p> By clicking the Sign up button you agree to our<br>
        <a href="#">Terms and Condition</a> and <a href="#">Privacy Policy</a>
        </p>
    </div>
    <script>
        function validatePassword() {
            let password = document.getElementById('password').value;
            let confirmPassword = document.getElementById('confirmPassword').value;
            if (password !== confirmPassword) {
                alert('Passwords do not match');
                return false;
            }
            return true;
        }
    </script>
    <p>Already have an account? <a href="hello.html">Login Here</a></p>
</body>
</html>
