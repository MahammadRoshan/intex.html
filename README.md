# intex.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Voice Website</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      text-align: center;
    }

    .container {
      padding: 80px 20px;
    }

    h1 {
      font-size: 40px;
    }

    p {
      font-size: 18px;
      opacity: 0.8;
    }

    button {
      padding: 12px 20px;
      border: none;
      background: #3b82f6;
      color: white;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 20px;
    }

    button:hover {
      background: #2563eb;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>🚀 My AI Website</h1>
    <p>Talk to the AI assistant using voice.</p>
    <button onclick="alert('AI is ready! Use voice icon below.')">
      Test AI
    </button>
  </div>

  <!-- ✅ YOUR AI VOICE ASSISTANT -->
  <script src="https://api.anvevoice.app/functions/v1/voice-assistant-embed-js?embedId=4646d823-0eb5-4473-9190-badb2683e8a6&position=bottom-right&theme=light"></script>

</body>
</html>
