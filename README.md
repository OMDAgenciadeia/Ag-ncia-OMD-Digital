<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OMD Agência Digital</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; color: #fff; background: #000; overflow-x: hidden; }
    header {
      position: relative;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: black;
    }
    header video {
      position: absolute;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    header .content {
      z-index: 1;
      max-width: 800px;
      padding: 20px;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .cta {
      padding: 15px 30px;
      background: #00ffae;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .cta:hover {
      background: #00c790;
    }
    section {
      padding: 80px 20px;
      text-align: center;
      background: #111;
    }
    .reveal {
      opacity: 0;
      transform: translateY(40px);
      transition: all 1s ease;
    }
    .reveal.active {
      opacity: 1;
      transform: translateY(0);
    }
    footer {
      background: #000;
      color: #888;
      padding: 30px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <video autoplay muted loop playsinline>
      <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
    </video>
    <div class="content">
      <h1>Transforme seu atendimento com IA no WhatsApp</h1>
      <button class="cta">Fale com nossa IA</button>
    </div>
  </header>

  <section class="reveal">
    <h2>Atendimento 24/7</h2>
    <p>Automatize respostas, gere vendas, colete leads enquanto dorme.</p>
  </section>

  <section class="reveal">
    <h2>Tráfego Inteligente</h2>
    <p>Gestão de tráfego com foco em conversão e otimização de verba.</p>
  </section>

  <section class="reveal">
    <h2>CRM Integrado</h2>
    <p>Organize e acompanhe seus contatos com inteligência artificial.</p>
  </section>

  <footer>
    <p>OMD Agência Digital &copy; 2025</p>
  </footer>

  <script>
    const reveals = document.querySelectorAll('.reveal');
    window.addEventListener('scroll', () => {
      for (let i = 0; i < reveals.length; i++) {
        const windowHeight = window.innerHeight;
        const revealTop = reveals[i].getBoundingClientRect().top;
        const revealPoint = 150;

        if (revealTop < windowHeight - revealPoint) {
          reveals[i].classList.add('active');
        }
      }
    });
  </script>
</body>
</html>
