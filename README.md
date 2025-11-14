<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio - Eduarda Escócio</title>

  <style>
    /* --- CONFIGURAÇÕES GERAIS --- */
    body {
      margin: 0;
      font-family: Epilogue, sans-serif;
      color: #2D2D2D;
      background: white;
    }

    section {
      padding: 42px 24px;
    }

    .container {
      width: 100%;
      max-width: 1280px;
      margin: auto;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
    }

    /* --- HEADER --- */
    header {
      padding: 24px 42px;
      display: flex;
      justify-content: flex-end;
      gap: 24px;
      flex-wrap: wrap;
    }

    header .nav-item {
      font-size: 17px;
      cursor: pointer;
    }

    /* --- HERO --- */
    .hero {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      padding: 50px 24px;
      align-items: center;
      justify-content: center;
    }

    .hero img {
      width: 100%;
      max-width: 420px;
      border-radius: 8px;
      object-fit: cover;
    }

    .hero-text {
      max-width: 620px;
      min-width: 280px;
    }

    .hero-text h1 {
      font-family: 'against', sans-serif;
      font-size: 48px;
      margin: 0;
    }

    .hero-text .subtitle {
      font-size: 20px;
      line-height: 30px;
      font-family: "Atkinson Hyperlegible", sans-serif;
      margin-bottom: 12px;
    }

    .button {
      background: #2D2D2D;
      color: white;
      padding: 18px 48px;
      font-size: 18px;
      font-weight: 600;
      display: inline-flex;
      cursor: pointer;
      border-radius: 4px;
      margin-top: 20px;
    }

    /* --- CARDS GERAIS --- */
    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 24px;
      justify-content: center;
    }

    .card {
      flex: 1 1 300px;
      max-width: 370px;
      padding: 42px 32px;
      text-align: center;
      border-radius: 8px;
    }

    .card-title {
      font-size: 24px;
      font-weight: 600;
      margin-top: 12px;
    }

    .card-text {
      font-size: 17px;
      line-height: 27px;
      margin-top: 8px;
    }

    /* --- SOCIAL MÍDIA --- */
    .social-item {
      flex: 1 1 300px;
      max-width: 395px;
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .social-item img {
      width: 100%;
      border-radius: 8px;
    }

    .social-title {
      font-size: 20px;
      font-weight: 600;
    }

    /* --- FOOTER --- */
    footer {
      padding: 42px 24px 86px;
      text-align: center;
    }

    footer h2 {
      font-size: 28px;
      font-weight: 600;
    }

    .footer-icons {
      display: flex;
      gap: 24px;
      margin-top: 24px;
      justify-content: center;
    }

    .footer-icons div {
      width: 36px;
      height: 36px;
      background: black;
      border-radius: 4px;
    }

    /* --------- RESPONSIVIDADE --------- */

    @media (max-width: 768px) {
      .hero-text h1 {
        font-size: 38px;
      }

      .hero-text .subtitle {
        font-size: 18px;
      }

      section {
        padding: 32px 20px;
      }

      .button {
        padding: 16px 36px;
        font-size: 16px;
      }
    }

    @media (max-width: 480px) {
      header {
        justify-content: center;
        gap: 16px;
      }

      .hero-text h1 {
        font-size: 32px;
      }

      .hero {
        padding: 32px 16px;
      }

      .card {
        padding: 32px 20px;
      }

      footer h2 {
        font-size: 24px;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <!-- HEADER -->
    <header>
      <div class="nav-item">About</div>
      <div class="nav-item">Work</div>
      <div class="nav-item">Contact</div>
    </header>

    <!-- HERO -->
    <section class="hero">
      <img src="img/g405696.png" alt="foto">

      <div class="hero-text">
        <div class="subtitle">
          UI/UX Designer | Software Engineering | Agile Methodologies
        </div>

        <h1>Eduarda Escócio</h1>

        <p>
          Estudante de Engenharia de Software da Universidade Federal do Ceará.
          Líder de Comunicação e Mídias do Projeto ARES. <br>
          UI/UX Designer - Oráculos <br>
          Psicologia do Usuário | Padrões de Design | Interação Humano-Computador.
        </p>

        <div class="button">Contate-me</div>
      </div>
    </section>

    <!-- CARDS -->
    <section>
      <div class="cards">

        <div class="card">
          <img src="img/Rectangle 25.png">
          <div class="card-title">Metodologias Ágeis</div>
          <div class="card-text">
            Experiência com ferramentas como ClickUp, Jira, Trello...
          </div>
        </div>

        <div class="card">
          <img src="img/Skills Card Icon.png">
          <div class="card-title">User Experience</div>
          <div class="card-text">
            Além da estética: aplico psicologia do consumidor para criar interfaces intuitivas.
          </div>
        </div>

        <div class="card">
          <img src="img/Skills Card Icon2.png">
          <div class="card-title">Criatividade</div>
          <div class="card-text">
            Construo projetos variados para desenvolver senso crítico e inovação.
          </div>
        </div>

      </div>
    </section>

    <!-- SOCIAL MEDIA -->
    <section>
      <h2 style="text-align:center">Social mídia</h2>

      <div class="cards">

        <div class="social-item">
          <img src="https://placehold.co/395x330">
          <div class="social-title">PROJETO ARES</div>
          <p>Análise de Riscos e Estratégias em Segurança <br>
            <span style="color:#0063AF">Instagram do projeto</span>
          </p>
        </div>

        <div class="social-item">
          <img src="https://placehold.co/395x330">
          <div class="social-title">Projeto Meu Amigo Perro</div>
          <p>Projeto social para cuidar dos cachorros da UFC. <br>
            <span style="color:#FF00FB">Instagram do projeto</span>
          </p>
        </div>

        <div class="social-item">
          <img src="https://placehold.co/395x330">
          <div class="social-title">Centro Acadêmico Margaret Hamilton</div>
          <p>Centro Acadêmico de Engenharia de Software. <br>
            <span style="color:#001890">Instagram do Centro Acadêmico</span>
          </p>
        </div>

      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      <h2>Vamos criar algo inovador juntos?</h2>

      <div class="footer-icons">
        <div></div>
        <div></div>
        <div></div>
      </div>
    </footer>

  </div>

</body>

</html>
