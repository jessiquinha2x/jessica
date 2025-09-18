<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Site Acessível - Naruto</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="bg-dark text-white p-3" role="banner">
    <h1 tabindex="0">Naruto Uzumaki</h1>
    <nav aria-label="Menu principal">
      <ul class="nav">
        <li class="nav-item"><a class="nav-link text-white" href="#sobre" tabindex="0">Sobre</a></li>
        <li class="nav-item"><a class="nav-link text-white" href="#habilidades" tabindex="0">Habilidades</a></li>
        <li class="nav-item"><a class="nav-link text-white" href="#galeria" tabindex="0">Galeria</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="sobre" class="container mt-4" aria-labelledby="titulo-sobre">
      <h2 id="titulo-sobre" tabindex="0">Sobre Naruto</h2>
      <p tabindex="0">Naruto Uzumaki é um ninja da Vila da Folha que sonha em se tornar Hokage. Determinado, corajoso e com um forte senso de justiça.</p>
    </section>

    <section id="habilidades" class="container mt-4" aria-labelledby="titulo-habilidades">
      <h2 id="titulo-habilidades" tabindex="0">Habilidades</h2>
      <ul>
        <li tabindex="0">Rasengan</li>
        <li tabindex="0">Modo Sábio</li>
        <li tabindex="0">Kurama Chakra Mode</li>
      </ul>
    </section>

    <section id="galeria" class="container mt-4" aria-labelledby="titulo-galeria">
      <h2 id="titulo-galeria" tabindex="0">Galeria</h2>
      <img src="naruto.jpg" alt="Naruto em pose de combate" class="img-fluid" />
    </section>
  </main>

  <footer class="bg-dark text-white text-center p-3" role="contentinfo">
    <p tabindex="0">© 2025 Site Acessível - Naruto</p>
  </footer>

  <script src="https://unpkg.com/scrollreveal"></script>
  <script>
    ScrollReveal().reveal('section', { delay: 300 });
  </script>
</body>
</html>
