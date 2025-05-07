<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perfil de GitHub</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #fef0f6;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .profile-card {
      background: #fff;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      width: 350px;
      text-align: center;
      padding: 20px;
      position: relative;
      overflow: hidden;
    }
    .profile-card img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
    }
    .profile-card h2 {
      margin: 10px 0;
      font-size: 1.5rem;
      color: #333;
    }
    .profile-card p {
      font-size: 1rem;
      color: #666;
      margin-bottom: 20px;
    }
    .social-icons {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }
    .social-icons a {
      text-decoration: none;
      color: #ff66b2;
      font-size: 1.5rem;
      transition: transform 0.3s ease;
    }
    .social-icons a:hover {
      transform: scale(1.2);
    }
    /* Animaciones */
    @keyframes typing {
      0% { width: 0; }
      100% { width: 100%; }
    }
    .typing-effect {
      display: inline-block;
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid #ff66b2;
      animation: typing 3s steps(30) 1s forwards;
    }
    .bubble {
      position: absolute;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      width: 20px;
      height: 20px;
      background-color: #ff66b2;
      border-radius: 50%;
      animation: bubble 3s infinite;
    }
    .bubble:nth-child(2) {
      animation-delay: 1s;
      left: 60%;
    }
    .bubble:nth-child(3) {
      animation-delay: 2s;
      left: 40%;
    }
    @keyframes bubble {
      0% { transform: translateY(0); opacity: 1; }
      50% { transform: translateY(-20px); opacity: 0.5; }
      100% { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="profile-card">
    <img src="https://via.placeholder.com/120" alt="Foto de perfil">
    <h2>María González</h2>
    <p class="typing-effect">Desarrolladora Frontend</p>
    <div class="social-icons">
      <a href="https://github.com/mariagonzalez" target="_blank">🐱</a>
      <a href="https://www.linkedin.com/in/mariagonzalez" target="_blank">🔗</a>
      <a href="https://twitter.com/mariagonzalez" target="_blank">🐦</a>
    </div>
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>
  </div>

</body>
</html>
