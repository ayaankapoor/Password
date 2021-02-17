# Password
<!DOCTYPE html>
<html>
    <head>
        <style>
            body {
            background-color:forestgreen;
            }
        </style>
        <title>The Password</title>
    </head>
    <body>
        <script>
            function checkPassword() {
                var password = document.getElementById("passwordBox");
                var passwordText = password.value;
                if(passwordText == "Ayaan2009") {
                    return true;
                }
                alert("ACCESS DENIED!!!");
                return false;
            }
        </script>
        <p style="font-size: 30pt;">AYAAN'S WEBPAGE</p>
        <p>Please enter the password to view this site</p>
        <p>Password:<input id="passwordBox" type= "password"/></p>
        <a href="https://ayaankapoor.github.io/" onclick="return checkPassword();">
            Click here to submit password and view this site
        </a>
    </body>
</html>
