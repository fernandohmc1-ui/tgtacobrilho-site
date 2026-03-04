<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TGTACOBRILHO | Pisos, Decks e Escadas</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <script src="https://unpkg.com/scrollreveal"></script>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:'Poppins', sans-serif; background:#f8f6f3; color:#333; }

    header {
      background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)), url('./images/foto1.jpg');
      background-size:cover;
      background-position:center;
      height:95vh;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:white;
      position:relative;
      padding:20px;
    }

    .logo {
      position:absolute;
      top:30px;
      left:50px;
      font-weight:700;
      font-size:1.3rem;
      letter-spacing:2px;
    }

    header h1 { font-size:3rem; margin-bottom:20px; }
    header p { font-size:1.2rem; margin-bottom:30px; }

    .btn {
      background:#c49a6c;
      color:white;
      padding:15px 35px;
      border-radius:40px;
      text-decoration:none;
      font-weight:600;
      transition:0.3s;
      display:inline-block;
    }

    .btn:hover { background:#a87e50; transform:scale(1.05); }

    section { padding:90px 10%; }

    .section-title {
      text-align:center;
      font-size:2.3rem;
      margin-bottom:60px;
      color:#5a3e2b;
    }

    .services, .testimonials {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:40px;
    }

    .service-card, .testimonial-card {
      background:white;
      padding:35px;
      border-radius:20px;
      box-shadow:0 15px 35px rgba(0,0,0,0.08);
      transition:0.4s;
    }

    .service-card:hover { transform:translateY(-12px); }

    .gallery {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
      gap:25px;
    }

    .gallery img {
      width:100%;
      border-radius:20px;
      box-shadow:0 15px 30px rgba(0,0,0,0.15);
    }

    .cta {
      background:#5a3e2b;
      color:white;
      text-align:center;
      border-radius:25px;
      padding:70px 20px;
    }

    footer {
      background:#3e2a1f;
      color:white;
      text-align:center;
      padding:25px;
    }

    .whatsapp-float {
      position:fixed;
      bottom:25px;
      right:25px;
      background:#25D366;
      color:white;
      font-size:28px;
      width:60px;
      height:60px;
      border-radius:50%;
      display:flex;
      align-items:center;
      justify-content:center;
      text-decoration:none;
    }

    @media (max-width:768px) {
      header h1 { font-size:2rem; }
      .logo { left:20px; }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">TGTACOBRILHO<br><span style="font-weight:300;font-size:0.8rem;">João Pessoa - Paraíba</span></div>
  <div>
    <h1>Especialistas em Pisos e Estruturas de Madeira</h1>
    <p>Instalação, restauração e acabamento profissional para pisos, decks, escadas e assoalhos de madeira.</p>
    <a href="#contato" class="btn">Solicitar Orçamento</a>
  </div>
</header>

<section>
  <h2 class="section-title">Nossos Serviços</h2>
  <div class="services">
    <div class="service-card"><h3>Pisos de Madeira</h3><p>Instalação profissional com acabamento impecável e alta durabilidade.</p></div>
    <div class="service-card"><h3>Decks</h3><p>Projetos sob medida para áreas externas com resistência e elegância.</p></div>
    <div class="service-card"><h3>Escadas</h3><p>Escadas modernas e clássicas com segurança e sofisticação.</p></div>
    <div class="service-card"><h3>Restauração</h3><p>Lixamento, aplicação de verniz e revitalização completa do seu assoalho.</p></div>
  </div>
</section>

<section>
  <h2 class="section-title">Projetos Realizados</h2>
  <div class="gallery">
    <img src="./images/foto1.jpg" alt="Projeto 1">
    <img src="./images/foto2.jpg" alt="Projeto 2">
    <img src="./images/foto3.jpg" alt="Projeto 3">
  </div>
</section>

<section>
  <h2 class="section-title">O que nossos clientes dizem</h2>
  <div class="testimonials">
    <div class="testimonial-card"><p>"Trabalho impecável! Meu piso ficou novo novamente."</p></div>
    <div class="testimonial-card"><p>"Pontualidade e qualidade acima do esperado."</p></div>
    <div class="testimonial-card"><p>"Acabamento de alto padrão."</p></div>
  </div>
</section>

<section class="cta" id="contato">
  <h2>Solicite seu orçamento</h2>
  <p style="margin:25px 0;">Fale diretamente conosco pelo WhatsApp.</p>
  <a href="https://wa.me/5583988639196" target="_blank" class="btn">Falar no WhatsApp</a>
</section>

<footer>
  © 2026 TGTACOBRILHO - João Pessoa/PB - Todos os direitos reservados
</footer>

<a href="https://wa.me/5583988639196" class="whatsapp-float" target="_blank">☎</a>

<script>
  ScrollReveal().reveal('.service-card, .gallery img, .testimonial-card', {
    distance:'50px',
    duration:1000,
    origin:'bottom',
    interval:200
  });
</script>

</body>
</html>
