<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy New Year 2026, Gaurish!</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }body {
  height: 100vh;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.container {
  text-align: center;
  z-index: 2;
  animation: fadeIn 2s ease-in-out;
}

h1 {
  font-size: 3.5rem;
  margin-bottom: 20px;
  animation: glow 2s infinite alternate;
}

h2 {
  font-size: 2.2rem;
  margin-bottom: 10px;
}

p {
  font-size: 1.2rem;
  opacity: 0.9;
}

.year {
  font-size: 5rem;
  font-weight: bold;
  margin-top: 20px;
  color: #ffd700;
}

.footer {
  margin-top: 40px;
  font-size: 0.9rem;
  opacity: 0.7;
}

@keyframes glow {
  from {
    text-shadow: 0 0 10px #ffcc00, 0 0 20px #ffcc00;
  }
  to {
    text-shadow: 0 0 20px #ff6600, 0 0 40px #ff6600;
  }
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Fireworks */
.firework {
  position: absolute;
  width: 6px;
  height: 6px;
  background: white;
  border-radius: 50%;
  animation: explode 1.5s ease-out infinite;
}

@keyframes explode {
  0% {
    transform: scale(0);
    opacity: 1;
  }
  100% {
    transform: scale(20);
    opacity: 0;
  }
}

  </style>
</head>
<body>
  <div class="container">
    <h1>🎉 Happy New Year 🎉</h1>
    <h2>Dear Gaurish,</h2>
    <p>May this new year bring you happiness, success, good health,<br />
       and countless reasons to smile.</p>
    <div class="year">2026</div>
    <div class="footer">Wishing you a bright and amazing year ahead ✨</div>
  </div>  <!-- Fireworks elements -->  <div class="firework" style="top:20%; left:30%; animation-delay:0s"></div>
  <div class="firework" style="top:40%; left:70%; animation-delay:0.5s"></div>
  <div class="firework" style="top:60%; left:20%; animation-delay:1s"></div>
  <div class="firework" style="top:25%; left:80%; animation-delay:1.2s"></div></body>
</html>
