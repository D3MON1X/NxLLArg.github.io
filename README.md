<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>???</title>
  <style>
    body {
      background-color: #111;
      color: #ffffffff;
      font-family: monospace;
      text-align: center;
      padding-top: 100px;
    }
    input, button {
      background-color: #000;
      color: #ffffff;
      border: 1px solid #ffffffff;
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

  <h1>greetings, d3mon1x_ underworld</h1>
  <h2>report your findings.</h2>
  <input type="text" id="codeInput" placeholder="insert findings here">
  <button onclick="checkCode()">enter.</button>
  <div id="message"></div>

  <script>
    const secrets = {
      "nxll": "all i get looking at them is the phrase 'define reality'...",
      "stardom": "look to the night, what do you see?",
      "blair": "your own pain or tragedy",
      "cian": "GINGERRRRRRRRRRRRRRRRRRRRRRR",
      "reality": "https://drive.google.com/file/d/1c4GvQGiK7CdPqTXPxDhtA_U0J6hWc_cw/view?usp=sharing",
      "penitence": "https://drive.google.com/file/d/1ziSTjeiJXzrQ70-_HfwziUbxMJYEXBhc/view?usp=drive_link",
      "flavor rave": "locked and loaded... RAVE!",
      "pale archives": "https://www.youtube.com/@TeamSpiceRack",
      "komi": "https://www.youtube.com/watch?v=2L-XbWzOdoI",
      "draco": "https://www.youtube.com/watch?v=2Ea7EfrRL8o",
      "kris": "deltarune (btw kris this is ashley ooc i love you)",
      "shads": "Daratike dirote hatimati",
      "nick": "todo sobre ti es perfecto",
      "zerobelow": "cassain... where is he... WHERE IS H-",
      "paragon": "health... mirrors... that's all there is",
      "capsic": "you know passion is dangerous... right? ... you make passion safe.",
      "zankow": "you're greater than you know. greater than i see myself as... good luck, kid.",
      "styxsi": "You... i know what you are boun clover."
    };

    function checkCode() {
      const input = document.getElementById("codeInput").value.toLowerCase();
      const messageDiv = document.getElementById("message");

      if (secrets[input]) {
        messageDiv.textContent = secrets[input];
      } else {
        messageDiv.textContent = "let's try something else, couldn't find anything here.";
      }
    }
  </script>

</body>

