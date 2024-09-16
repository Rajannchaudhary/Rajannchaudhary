<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proposal for Juli</title>
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
        #proposal {
            font-size: 32px;
            font-weight: bold;
            color: #ff4500;
        }
    </style>
</head>
<body>
    <div>
        <div id="message">Click the button below for a special message:</div>
        <button onclick="revealProposal()">Reveal Proposal</button>
        <div id="proposal"></div>
    </div>
    <script>
        function revealProposal() {
            const proposalDiv = document.getElementById('proposal');
            proposalDiv.innerHTML = 'Juli, will you marry me?';
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
