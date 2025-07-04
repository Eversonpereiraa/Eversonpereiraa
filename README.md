<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Everson Pereira - Portfólio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #333;
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 2.5rem;
    }
    #typed {
      color: #007bff;
    }
    .icons {
      margin-top: 20px;
      font-size: 1.2rem;
    }
    .icons i {
      margin: 0 10px;
      color: #007bff;
    }
    .section {
      margin-top: 30px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
  </style>
</head>
<body>

  <h1>👨‍💻 Olá! Eu sou <span id="typed"></span></h1>
  <p class="section">
    Desenvolvedor Web & Web Designer apaixonado por transformar ideias em interfaces modernas e funcionais 🚀
  </p>

  <div class="section">
    <h3>🚀 O que eu faço:</h3>
    <ul style="list-style: none; padding: 0;">
      <li>✅ React.js, Node.js e PHP</li>
      <li>✅ HTML5, CSS3 + UX/UI Design</li>
      <li>✅ WordPress (temas e plugins)</li>
    </ul>
  </div>

  <div class="section">
    <h3>🛠 Tecnologias:</h3>
    <div class="icons">
      <i class="fab fa-js-square"></i>
      <i class="fab fa-react"></i>
      <i class="fab fa-node-js"></i>
      <i class="fab fa-php"></i>
      <i class="fab fa-html5"></i>
      <i class="fab fa-css3-alt"></i>
    </div>
  </div>

  <div class="section">
    <h3>📫 Contato:</h3>
    <p>📧 joseeversonti@gmail.com</p>
    <p>📍 PE, Brasil</p>
    <p><i class="fab fa-github"></i> github.com/seuusuario</p>
  </div>

  <script>
    new Typed('#typed', {
      strings: ['Everson Pereira', 'Desenvolvedor Web', 'Web Designer'],
      typeSpeed: 60,
      backSpeed: 30,
      loop: true
    });
  </script>

</body>
</html>
