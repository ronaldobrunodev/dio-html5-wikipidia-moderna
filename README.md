# dio-html5-wikipidia-moderna
Desafio de criação de um modelo em HTML da págia do Wikipidia

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wikipedia Moderna</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Wikipedia Moderna</h1>
      <nav>
        <ul>
          <li><a href="#">Página Inicial</a></li>
          <li><a href="#">História</a></li>
          <li><a href="#">Eventos</a></li>
          <li><a href="#">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <section class="hero">
    <div class="container">
      <h2>Descubra e aprenda</h2>
      <p>Explore milhares de artigos em diversos tópicos.</p>
      <form action="#" method="GET">
        <input type="search" name="search" placeholder="Pesquisar">
        <button type="submit">Buscar</button>
      </form>
    </div>
  </section>

  <section class="featured-articles">
    <div class="container">
      <h3>Artigos em destaque</h3>
      <div class="article-list">
        <article>
          <h4>Nome do Artigo 1</h4>
          <p>Um breve resumo sobre o artigo 1.</p>
        </article>
        <article>
          <h4>Nome do Artigo 2</h4>
          <p>Um breve resumo sobre o artigo 2.</p>
        </article>
        <!-- Adicione mais artigos aqui -->
      </div>
    </div>
  </section>
  <footer>
    <div class="container">
      <p>&copy; 2023 Wikipedia Moderna. Todos os direitos reservados.</p>
    </div>
  </footer>
</body>
</html>
