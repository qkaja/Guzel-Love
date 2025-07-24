<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Моя любовь — Гузель</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      color: #fff;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
      animation: fadeIn 2s ease-out;
    }

    p {
      font-size: 1.5em;
      margin: 0.5em auto;
      max-width: 600px;
      animation: fadeIn 2.5s ease-out;
    }

    .heart {
      font-size: 4em;
      animation: pulse 1.5s infinite;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 2em;
      margin: 1em;
      backdrop-filter: blur(8px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: slideUp 1.2s ease-out;
    }

    footer {
      margin-top: 2em;
      font-size: 0.9em;
      opacity: 0.8;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.15); }
      100% { transform: scale(1); }
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideUp {
      0% { transform: translateY(30px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>Я — Ермурат</h1>
    <p>Моё сердце навсегда принадлежит <strong>Гузель</strong>.</p>
    <p>С 18 января 2025 года началась наша история любви 💞</p>
    <p>Она — моя гиперактивная малышка, моя милая, мой смысл и вдохновение.</p>
    <p>Если ты видишь эту страницу — знай, любовь жива и она прекрасна ✨</p>
  </div>

  <footer>
    С любовью, Ермурат — для Гузель 💖
  </footer>
</body>
</html>
