<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Invitación Beatlemaníaca</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@600&display=swap');

  body {
    background: linear-gradient(270deg, #ff9a9e, #fad0c4, #fbc2eb, #a6c1ee);
    background-size: 800% 800%;
    font-family: 'Baloo 2', cursive;
    color: #fff;
    text-align: center;
    padding: 40px;
    animation: bgshift 10s ease infinite;
  }

  @keyframes bgshift {
    0% { background-position: 0% 50%; }
    100% { background-position: 100% 50%; }
  }

  .invitacion {
    background: rgba(0, 0, 0, 0.4);
    border: 4px solid #fff;
    border-radius: 20px;
    padding: 40px;
    max-width: 600px;
    margin: 50px auto;
    box-shadow: 0 0 20px rgba(255, 255, 255, 0.6);
  }

  h1 {
    font-size: 3em;
    margin-bottom: 10px;
    text-shadow: 2px 2px 10px #ffeb3b;
  }

  h2 {
    color: #ffeb3b;
    margin-bottom: 30px;
  }

  p {
    font-size: 1.3em;
    line-height: 1.5;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.6);
  }

  .vinilo {
    width: 150px;
    height: 150px;
    background: radial-gradient(circle at 50% 50%, #222 30%, #000 70%);
    border-radius: 50%;
    margin: 20px auto;
    position: relative;
    animation: spin 10s linear infinite;
  }

  .vinilo::before {
    content: "";
    position: absolute;
    top: 45%;
    left: 45%;
    width: 20px;
    height: 20px;
    background: #ffeb3b;
    border-radius: 50%;
  }

  @keyframes spin {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  .boton {
    background: #ffeb3b;
    color: #000;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 30px;
    font-size: 1.2em;
    transition: 0.3s;
    display: inline-block;
  }

  .boton:hover {
    background: #fff;
    transform: scale(1.1);
  }

  footer {
    margin-top: 40px;
    font-size: 0.9em;
  }

  @media (max-width: 480px) {
    h1 { font-size: 2em; }
    .invitacion { padding: 20px; }
  }
</style>
</head>
<body>
  <div class="invitacion">
    <div class="vinilo"></div>
    <h1>¡Ven a la Fiesta De Conchita!</h1>
    <h2>Estilo años 70 🌼✨</h2>
    <p>
      Ponte tu mejor ropa psicodélica y prepárate para una noche llena de paz, amor y música de los Beatles.
    </p>
    <p>
      📍 Lugar: Avenida 3 sur 10911 LOMA ENCANTADA, SALON JARDIN "EL REHILETE" <br>
      📅 Fecha: VIERNES 28 DE NOVIEMBRE <br>
      🕖 Hora: 6:00 PM
    </p>
    <a href="https://www.youtube.com/watch?v=QDYfEBY9NM4" target="_blank" class="boton">
      🎶 Escuchar "Let It Be"
    </a>
  </div>
  <footer>
    <p>Con amor y ritmo — Inspirado en The Beatles 💛</p>
  </footer>
</body>
</html>
