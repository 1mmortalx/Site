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
            position: relative; /* Make sure elements are positioned relative to the body */
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

        /* Style for the message box */
        #message-box {
            display: none; /* Hidden by default */
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #7289DA;
            color: white;
            padding: 20px;
            border-radius: 10px;
            font-size: 24px;
            z-index: 10; /* Ensure it appears on top */
        }
    </style>

    <!-- Script to handle message display -->
    <script>
        function showMessage() {
            // Show the message box
            const messageBox = document.getElementById("message-box");
            messageBox.style.display = "block";
            
            // Hide the message after 30 seconds (30000 ms)
            setTimeout(function() {
                messageBox.style.display = "none";
            }, 30000);
        }
    </script>
</head>
<body>
    <div class="button-container">
        <h1>Join Our Discord Server</h1>
        <div class="buttons">
            <a href="https://discord.gg/KCAN2E9WfQ" class="join-button">Join</a>
            <!-- Updated About Us button to show a message on click -->
            <button class="about-button" onclick="showMessage()">About Us</button>
        </div>
    </div>

    <!-- The message box that will display the text -->
    <div id="message-box">
        We are a Roblox Team that created a community game and are ready to welcome new players!
    </div>
</body>
</html>
