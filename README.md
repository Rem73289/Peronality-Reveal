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
        "You're a stealthy genius.",
        "You're a chaotic dreamer.",
        "You're a quiet rebel.",
        "You're a bold visionary.",
        "You're a secret comedian.",
        "You're a cosmic wanderer.",
        "You're a fearless trailblazer.",
        "You're a quirky inventor.",
        "You're a hidden poet.",
        "You're a radiant optimist.",
        "You're a mischievous strategist.",
        "You're a timeless adventurer.",
        "You're a gentle powerhouse.",
        "You're a dazzling enigma.",
        "You're a playful philosopher.",
        "You're a cunning alchemist.",
        "You're a serene daredevil.",
        "You're a whimsical mastermind.",
        "You're a fierce daydreamer.",
        "You're a subtle conqueror.",
        "You're a vibrant chameleon.",
        "You're a rogue storyteller.",
        "You're a mystic observer.",
        "You're a spirited trickster.",
        "You're a lunar architect."
      ];
      const randomTrait = traits[Math.floor(Math.random() * traits.length)];
      document.getElementById("result").innerText = randomTrait;
    }
  </script>
</body>
</html>
