<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virus Alert</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8d7da;
            color: #721c24;
            text-align: center;
            padding-top: 50px;
        }
        .alert-box {
            border: 2px solid #f5c6cb;
            padding: 20px;
            margin: auto;
            width: 50%;
            border-radius: 5px;
            background-color: #f8d7da;
        }
        .btn {
            padding: 10px 20px;
            background-color: #f5c6cb;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="alert-box">
        <h1>Warning!</h1>
        <p>Your system has been infected with a virus!</p>
        <button class="btn" onclick="triggerAlert()">Click here to fix it</button>
    </div>

    <script>
        function triggerAlert() {
            alert("Just kidding! Hilton just created a fake virus simulation. No harm done!");
        }
    </script>
</body>
</html>
