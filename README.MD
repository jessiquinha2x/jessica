

  <!-- Link de pular para o conteúdo -->
  <a class="skip-link" href="#conteudo-principal">Ir direto para o conteúdo</a>

  <!-- Barra de acessibilidade -->
  <div class="acessibilidade-bar" role="region" aria-label="Barra de acessibilidade">
    <button id="btnMenuAcess" class="btn btn-dark btn-sm"
            aria-haspopup="dialog"
            aria-controls="menuAcess"
            aria-expanded="false">
      Menu de acessibilidade
    </button>
  </div>

  <!-- Menu de acessibilidade (dialog) -->
  <div id="menuAcess"
       class="menu-acessibilidade"
       role="dialog"
       aria-modal="true"
       aria-labelledby="titleMenuAcess"
       aria-describedby="descMenuAcess"
       hidden>
    <div class="menu-acessibilidade__content" role="document">
      <div class="d-flex justify-content-between align-items-start">
        <div>
          <h2 id="titleMenuAcess" class="h5 mb-1">Ajustes de acessibilidade</h2>
          <p id="descMenuAcess" class="small mb-3">Use as opções abaixo para personalizar a leitura.</p>
        </div>
        <button id="btnFecharMenu" class="btn btn-outline-secondary btn-sm" aria-label="Fechar menu de acessibilidade">
          Fechar
        </button>
      </div>

      <div class="row g-2">
        <div class="col-12 col-md-6">
          <div class="d-grid gap-2">
            <button class="btn btn-primary" id="aumentarFonte">Aumentar fonte</button>
            <button class="btn btn-primary" id="diminuirFonte">Diminuir fonte</button>
            <button class="btn btn-outline-primary" id="resetFonte">Resetar fonte</button>
          </div>
        </div>

        <div class="col-12 col-md-6">
          <div class="d-grid gap-2">
            <button class="btn btn-warning" id="toggleContraste" aria-pressed="false">Alto contraste</button>
            <button class="btn btn-warning" id="toggleLinks" aria-pressed="false">Destacar links</button>
            <button class="btn btn-warning" id="toggleAnimacoes" aria-pressed="false">Pausar animações</button>
          </div>
        </div>
      </div>

      <hr class="my-3" />
      <div class="d-flex gap-2">
        <button class="btn btn-outline-danger" id="resetTudo">Restaurar padrão</button>
      </div>
    </div>
  </div>

  <!-- Cabeçalho / Navegação -->
  <header class="border-bottom">
    <nav class="navbar navbar-expand-lg bg-body-tertiary" role="navigation" aria-label="Navegação principal">
      <div class="container">
        <a class="navbar-brand fw-bold" href="#" aria-label="Página inicial Naruto">Naruto</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navConteudo" aria-controls="navConteudo"
                aria-expanded="false" aria-label="Alternar navegação">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navConteudo">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item"><a class="nav-link" href="#sobre" aria-current="page">Sobre</a></li>
            <li class="nav-item"><a class="nav-link" href="#personagens">Personagens</a></li>
            <li class="nav-item"><a class="nav-link" href="#linha-do-tempo">Linha do tempo</a></li>
            <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li>
            <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <!-- Conteúdo principal -->
  <main id="conteudo-principal" role="main">
    <!-- Hero -->
    <section class="hero py-5" aria-label="Introdução">
      <div class="container d-flex flex-column flex-lg-row align-items-center gap-4">
        <div class="flex-grow-1" data-sr="fade-up">
          <h1 class="display-5 fw-bold">O mundo de Naruto Uzumaki</h1>
          <p class="lead mb-3">
            Uma jornada de perseverança, amizade e superação no universo ninja.
          </p>
          <div class="d-flex gap-2">
            <a class="btn btn-primary" href="#sobre">Começar</a>
            <a class="btn btn-outline-primary" href="#personagens">Conheça o elenco</a>
          </div>
        </div>
        <figure class="m-0 text-center" data-sr="fade-in">
          <img
            src="https://upload.wikimedia.org/wikipedia/en/9/94/NarutoCoverTankobon1.jpg"
            class="img-fluid rounded shadow"
            style="max-width: 280px"
            alt="Capa do mangá de Naruto mostrando o personagem Naruto Uzumaki em traje laranja."
            width="280"
            height="420"
            loading="lazy"
          />
          <figcaption class="small mt-2 text-muted">Arte de capa oficial do volume 1 (uso educacional).</figcaption>
        </figure>
      </div>
    </section>

    <hr class="my-0" />

    <!-- Sobre -->
    <section id="sobre" class="py-5" aria-labelledby="titulo-sobre">
      <div class="container">
        <h2 id="titulo-sobre" class="h3 fw-bold mb-3">Sobre Naruto</h2>
        <p data-sr="fade-up">
          Naruto é uma série de mangá e anime que acompanha Naruto Uzumaki, um jovem ninja
          que sonha em se tornar Hokage, o líder de sua vila. A narrativa explora temas como
          pertencimento, resiliência e o impacto dos laços humanos.
        </p>
        <p data-sr="fade-up" data-sr-delay="100">
          Ao longo da história, Naruto enfrenta desafios internos e externos, buscando quebrar
          ciclos de ódio e provar que reconhecimento nasce de escolhas e atitudes.
        </p>
      </div>
    </section>

    <!-- Personagens -->
    <section id="personagens" class="py-5 bg-body-tertiary" aria-labelledby="titulo-personagens">
      <div class="container">
        <h2 id="titulo-personagens" class="h3 fw-bold mb-4">Personagens principais</h2>
        <div class="row g-4">
          <article class="col-md-4" role="article" aria-labelledby="card-naruto-title" tabindex="0" data-sr="zoom-in">
            <div class="card h-100">
              <img src="https://upload.wikimedia.org/wikipedia/en/7/76/Naruto_Uzumaki.png"
                   class="card-img-top"
                   alt="Naruto Uzumaki sorrindo, usando bandana da Vila da Folha."
                   width="480" height="640" loading="lazy">
              <div class="card-body">
                <h3 id="card-naruto-title" class="h5 card-title">Naruto Uzumaki</h3>
                <p class="card-text">Energia inesgotável e empatia. Sonha em se tornar Hokage e proteger seus amigos.</p>
              </div>
            </div>
          </article>

          <article class="col-md-4" role="article" aria-labelledby="card-sasuke-title" tabindex="0" data-sr="zoom-in" data-sr-delay="100">
            <div class="card h-100">
              <img src="https://upload.wikimedia.org/wikipedia/en/c/c1/Sasuke_Uchiha.png"
                   class="card-img-top"
                   alt="Sasuke Uchiha com expressão séria e cabelo preto."
                   width="480" height="640" loading="lazy">
              <div cl
