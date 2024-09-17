<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Join Our Discord</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #2C2F33;
            font-family: Arial, sans-serif;
        }

        .button-container {
            text-align: center;
        }

        .buttons {
            display: flex;
            justify-content: center;
            gap: 20px; /* Space between the buttons */
        }

        .join-button, .about-button {
            background-color: #7289DA;
            color: white;
            border: none;
            padding: 20px 50px;
            font-size: 32px;
            border-radius: 12px;
            cursor: pointer;
            text-decoration: none;
        }

        .join-button:hover, .about-button:hover {
            background-color: #5b6eae;
        }

        h1 {
            color: white;
            margin-bottom: 30px;
            font-size: 36px;
        }
    </style>

    <!-- Script to change URL -->
    <script>
        // Change the displayed URL without reloading the page
        window.onload = function() {
            const newUrl = "discord.server.1m";
            window.history.replaceState({}, document.title, "/" + newUrl);
        };
    </script>
</head>
<body>
    <div class="button-container">
        <h1>Join Our Discord Server</h1>
        <div class="buttons">
            <a href="https://discord.gg/KCAN2E9WfQ" class="join-button">Join</a>
            <a href="about.html" class="about-button">About Us</a>
        </div>
    </div>
</body>
</html>
    
