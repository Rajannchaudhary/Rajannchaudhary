<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>this is my first code</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #message {
            font-size: 24px;
            margin-bottom: 20px;
        }
        #rejection {
            font-size: 32px;
            font-weight: bold;
            color: #ff4500;
        }
    </style>
</head>
<body>
    <div>
        <div id="message">Click the button below for a special message:</div>
        <button onclick="revealProposal()">Reveal rejection</button>
        <div id="rejection"></div>
    </div>
    <script>
        function revealrejection() {
            const rejectionDiv = document.getElementById('rejection');
            rejectionDiv.innerHTML = 'what is your name ?';
        }
    </script>
</body>
</html>

- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Rajannchaudhary/Rajannchaudhary is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
