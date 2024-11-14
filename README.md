<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feel-Good Message</title>
    <style>
        #message-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            font-family: 'Arial', sans-serif;
            text-align: center;
            color: #004d40;
            font-size: 1.5em;
        }

        #message {
            padding: 20px;
            border: 2px solid #004d40;
            border-radius: 15px;
            background-color: #e0f7fa;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div id="message-container">
        <div id="message"></div>
    </div>

    <script>
        function showHappyMessage() {
            const messageElement = document.getElementById('message');
            const message = "You are amazing and capable of great things! 😊";

            messageElement.textContent = message;
        }

        // Show the happy message when the page loads
        window.onload = showHappyMessage;
    </script>
</body>
</html>

<!---
yason969/yason969 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
