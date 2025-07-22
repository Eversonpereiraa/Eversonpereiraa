<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>José Everson</title>
  <style>
    body {
      font-family: 'Courier New', Courier, monospace;
      background-color: #0d1117;
      color: #c9d1d9;
      text-align: center;
      padding: 40px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .typewriter {
      display: inline-block;
      border-right: 2px solid #00ffcc;
      white-space: nowrap;
      overflow: hidden;
      animation: blinkCursor 0.75s step-end infinite;
    }

    @keyframes blinkCursor {
      from, to { border-color: transparent; }
      50% { border-color: #00ffcc; }
    }
  </style>
</head>
<body>

  <h1>👨‍💻 José Everson</h1>

  <p>
    <code class="typewriter" id="typewriter">&gt; </code><br />
    <strong>Desenvolvedor Web</strong> & <strong>Web Designer</strong> apaixonado por transformar ideias em experiências modernas e funcionais. 🚀
  </p>

  <hr />

  <h3>🚧 O que eu faço:</h3>
  <ul style="list-style: none; padding: 0;">
    <li>⚛️ Desenvolvimento de interfaces com <strong>React.js</strong></li>
    <li>🖥️ Back-end com <strong>Node.js</strong> e <strong>PHP</strong></li>
    <li>🎨 Criação de páginas com <strong>HTML5</strong>, <strong>CSS3</strong> e boas práticas de <strong>UX/UI Design</strong></li>
    <li>🔌 Desenvolvimento de temas e plugins para <strong>WordPress</strong></li>
  </ul>

  <hr />

  <h3>💡 Tecnologias que utilizo:</h3>
  <p>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" />
  </p>

  <hr />

  <h3>📫 Vamos conversar?</h3>
  <ul style="list-style: none; padding: 0;">
    <li>📧 E-mail: <a href="mailto:joseeversonti@gmail.com">joseeversonti@gmail.com</a></li>
    <li>🌍 Localização: Pernambuco, Brasil 🇧🇷</li>
    <li>📁 Repositórios aqui no GitHub – fique à vontade para explorar e colaborar!</li>
  </ul>

  <script>
    const el = document.getElementById("typewriter");
    const txt = "Olá, sou José Everson_";
    let index = 0;
    let forward = true;

    function typeWriter() {
      if (forward) {
        el.innerHTML = "> " + txt.substring(0, index++);
        if (index > txt.length) {
          forward = false;
          setTimeout(typeWriter, 1500); // pausa antes de apagar
          return;
        }
      } else {
        el.innerHTML = "> " + txt.substring(0, index--);
        if (index < 0) {
          forward = true;
        }
      }
      setTimeout(typeWriter, 100);
    }

    typeWriter();
  </script>

</body>
</html>
