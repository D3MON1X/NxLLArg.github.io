<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>???</title>
  <style>
    body {
      background-color: #111;
      color: #A020F0;
      font-family: monospace;
      text-align: center;
      padding-top: 100px;
    }
    input, button {
      background-color: #000;
      color: #A020F0;
      border: 1px solid #A020F0;
      padding: 10px;
      font-size: 16px;
    }
    #message {
      margin-top: 30px;
      font-size: 20px;
      white-space: pre-wrap;
    }
  </style>
</head>
<body>

  <h1>GREETINGS. USER; MANCHI</h1>
  <h2>PLEASE ENTER PASSWORD</h2>
  <input type="text" id="codeInput" placeholder="•••">
  <button onclick="checkCode()">Submit</button>
  <div id="message"></div>

  <script>
    const secrets = {
      "passion": "Pathetic Scumbag. He deserved everything he went through.",
      "manchi": "The GREATEST performer. No other can compete.",
      "subscribe": "https://www.youtube.com/@SubToAnAveragePerson",
      "average": "https://www.youtube.com/@SubToAnAveragePerson",
      "puppetage": "Wrong universe, scum.",
      "devil mario": "We have already WON.",
      "herosnackz": "gives off sister vibes.",
      "moros": "Sounds familiar, Where have I heard that name...?",
      "sour": "Heard about this EDM star, he could be a problem.",
      "sweet": "Heard some rumors about her being in a relationship with that Sour guy, she could be a problem as well.",
      "basted": "🤠",
      "styxsi": "HAI HAI HELLO HAI",
      "password": "Your Kidding, right?",
      "downfall": "https://docs.google.com/document/d/1iEz7jnQHbhvrBQa2BzdImWqR1AEm_UDFns2MQQ3GanU/edit?usp=sharing"
    };

    function checkCode() {
      const input = document.getElementById("codeInput").value.toLowerCase();
      const messageDiv = document.getElementById("message");

      if (secrets[input]) {
        messageDiv.textContent = secrets[input];
      } else {
        messageDiv.textContent = "Invalid Password. Please try another.";
      }
    }
  </script>

</body>
</html>
