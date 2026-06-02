# agrinho2026
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agro Forte | Futuro Sustentável</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins', sans-serif;
      scroll-behavior:smooth;
    }

    body{
      background:#f5fff5;
      color:#1f2937;
    }

    /* MENU */
    header{
      position:fixed;
      width:100%;
      top:0;
      left:0;
      z-index:1000;
      background:rgba(0,0,0,0.55);
      backdrop-filter:blur(6px);
    }

    nav{
      width:90%;
      margin:auto;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:18px 0;
    }

    nav h1{
      color:#fff;
      font-size:1.8rem;
    }

    nav ul{
      display:flex;
      gap:25px;
      list-style:none;
    }

    nav ul li a{
      text-decoration:none;
      color:#fff;
      transition:0.3s;
      font-weight:500;
    }

    nav ul li a:hover{
      color:#9be15d;
    }

    /* HERO */
    .hero{
      height:100vh;
      background:
      linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.6)),
      url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?q=80&w=1600&auto=format&fit=crop');

      background-size:cover;
      background-position:center;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:20px;
      color:white;
    }

    .hero-content{
      max-width:850px;
    }

    .hero h2{
      font-size:4rem;
      margin-bottom:20px;
    }

    .hero p{
      font-size:1.3rem;
      margin-bottom:35px;
    }

    .btn{
      display:inline-block;
      padding:15px 35px;
      background:#2e7d32;
      color:#fff;
      text-decoration:none;
      border-radius:40px;
      transition:0.3s;
      font-weight:600;
    }

    .btn:hover{
      background:#1b5e20;
      transform:translateY(-3px);
    }

    section{
      padding:90px 10%;
    }

    .title{
      text-align:center;
      margin-bottom:50px;
    }

    .title h2{
      font-size:2.7rem;
      color:#1b5e20;
      margin-bottom:10px;
    }

    .title p{
      max-width:700px;
      margin:auto;
      color:#4b5563;
    }

    /* CARDS */
    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
      gap:25px;
    }

    .card{
      background:#fff;
      padding:30px;
      border-radius:18px;
      box-shadow:0 8px 25px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-8px);
    }

    .card h3{
      color:#2e7d32;
      margin-bottom:15px;
      font-size:1.4rem;
    }

    /* SOBRE */
    .about{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
      align-items:center;
      gap:40px;
    }

    .about img{
      width:100%;
      border-radius:20px;
      box-shadow:0 10px 25px rgba(0,0,0,0.15);
    }

    .about-text h2{
      color:#1b5e20;
      font-size:2.5rem;
      margin-bottom:20px;
    }

    .about-text p{
      margin-bottom:18px;
      color:#374151;
    }

    /* NÚMEROS */
    .numbers{
      background:linear-gradient(120deg,#1b5e20,#43a047);
      color:white;
    }

    .numbers-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:30px;
      text-align:center;
    }

    .number-box h3{
      font-size:3rem;
      margin-bottom:10px;
    }

    /* CTA */
    .cta{
      text-align:center;
      background:#e8f5e9;
      margin:60px 10%;
      border-radius:30px;
      padding:60px 30px;
    }

    .cta h2{
      color:#1b5e20;
      font-size:2.5rem;
      margin-bottom:20px;
    }

    /* FOOTER */
    footer{
      background:#111827;
      color:#d1d5db;
      text-align:center;
      padding:40px 20px;
    }

    footer h3{
      margin-bottom:10px;
      color:#fff;
    }

    /* RESPONSIVO */
    @media(max-width:768px){

      nav{
        flex-direction:column;
        gap:15px;
      }

      nav ul{
        flex-wrap:wrap;
        justify-content:center;
      }

      .hero h2{
        font-size:2.6rem;
      }

      .hero p{
        font-size:1rem;
      }
    }
  </style>
</head>
<body>

  <!-- MENU -->
  <header>
    <nav>
      <h1>🌱 Agro Forte</h1>

      <ul>
        <li><a href="#inicio">Início</a></li>
        <li><a href="#tecnologia">Tecnologia</a></li>
        <li><a href="#sustentabilidade">Sustentabilidade</a></li>
        <li><a href="#producao">Produção</a></li>
      </ul>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero" id="inicio">
    <div class="hero-content">
      <h2>Agro Forte, Futuro Sustentável</h2>

      <p>
        Tecnologia, inovação e preservação ambiental trabalhando juntas
        para transformar o agronegócio e construir um futuro mais verde.
      </p>

      <a href="#tecnologia" class="btn">Explorar</a>
    </div>
  </section>

  <!-- TECNOLOGIA -->
  <section id="tecnologia">

    <div class="title">
      <h2>Tecnologia no Campo</h2>

      <p>
        A agricultura moderna utiliza inteligência, conectividade e automação
        para produzir mais com sustentabilidade.
      </p>
    </div>

    <div class="cards">

      <div class="card">
        <h3>🚜 Agricultura de Precisão</h3>

        <p>
          Sensores, drones e monitoramento digital ajudam produtores
          a reduzir desperdícios e aumentar a produtividade.
        </p>
      </div>

      <div class="card">
        <h3>🌐 Conectividade Rural</h3>

        <p>
          Internet e sistemas inteligentes tornam a gestão agrícola
          mais eficiente e integrada.
        </p>
      </div>

      <div class="card">
        <h3>🤖 Automação Inteligente</h3>

        <p>
          Máquinas modernas aumentam a eficiência da produção e reduzem
          impactos ambientais.
        </p>
      </div>

    </div>
  </section>

  <!-- SOBRE -->
  <section id="producao">

    <div class="about">

      <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=1200&auto=format&fit=crop" alt="Plantação sustentável">

      <div class="about-text">

        <h2>Produção com Responsabilidade</h2>

        <p>
          O futuro do agronegócio depende da união entre produção eficiente
          e preservação ambiental.
        </p>

        <p>
          Técnicas sustentáveis garantem alimentos de qualidade sem comprometer
          os recursos naturais das próximas gerações.
        </p>

        <p>
          Energia limpa, recuperação de áreas verdes e manejo inteligente
          fortalecem a economia e protegem o planeta.
        </p>

        <a href="#" class="btn">Saiba Mais</a>

      </div>
    </div>
  </section>

  <!-- NÚMEROS -->
  <section class="numbers" id="sustentabilidade">

    <div class="title">
      <h2 style="color:white;">Sustentabilidade em Ação</h2>

      <p style="color:#e5e7eb;">
        O agro sustentável combina inovação e responsabilidade ambiental.
      </p>
    </div>

    <div class="numbers-grid">

      <div class="number-box">
        <h3>80%</h3>
        <p>Economia de água com irrigação inteligente.</p>
      </div>

      <div class="number-box">
        <h3>50%</h3>
        <p>Redução de desperdícios através da tecnologia.</p>
      </div>

      <div class="number-box">
        <h3>100%</h3>
        <p>Compromisso com produção sustentável.</p>
      </div>

    </div>
  </section>

  <!-- CTA -->
  <div class="cta">
    <h2>O Agro Move o Mundo</h2>

    <p>
      Produzir com tecnologia e preservar o meio ambiente é o caminho
      para um futuro forte e sustentável.
    </p>

    <br>

    <a href="#" class="btn">Fazer Parte</a>
  </div>

  <!-- FOOTER -->
  <footer>

    <h3>🌱 Agro Forte</h3>

    <p>
