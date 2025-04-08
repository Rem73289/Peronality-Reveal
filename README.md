<!DOCTYPE html>
<html>
<head>
  <title>Discover Your Secret Trait</title>
  <style>
    body { text-align: center; font-family: Arial; margin-top: 100px; }
    button { background-color: red; color: white; padding: 20px 40px; font-size: 24px; border: none; cursor: pointer; }
    #result { margin-top: 20px; font-size: 20px; }
  </style>
</head>
<body>
  <h1>One Click to Unlock Your Hidden Vibe</h1>
  <button onclick="showTrait()">Discover Your Secret Trait</button>
  <p id="result"></p>
  <script>
    function showTrait() {
      const traits = [
        "You’re a stealthy genius.",
        "You’re a chaotic dreamer.",
        "You’re a quiet rebel.",
        "You’re a bold visionary.",
        "You’re a secret comedian."
      ];
      const randomTrait = traits[Math.floor(Math.random() * traits.length)];
      document.getElementById("result").innerText = randomTrait;
    }
  </script>
</body>
</html>
