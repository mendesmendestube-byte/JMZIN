<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Oficial do JMZIN</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #000;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #ff4040;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    .banner {
      background: url('https://via.placeholder.com/1200x400') no-repeat center center;
      background-size: cover;
      height: 400px;
    }
    .produtos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 40px 20px;
    }
    .produto {
      background-color: #222;
      padding: 20px;
      border-radius: 10px;
      max-width: 300px;
      text-align: center;
    }
    .produto img {
      width: 100%;
      border-radius: 10px;
    }
    .produto h2 {
      color: #ff4040;
      margin: 10px 0 5px;
    }
    .produto p {
      font-size: 14px;
    }
    footer {
      background-color: #000;
      color: #888;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Loja Oficial do JMZIN</h1>
    <p>Produtos exclusivos do canal JMZINBW</p>
  </header>
  <div class="banner"></div>
  <nav>
    <a href="#camisas">Camisas</a>
    <a href="#faixas">Faixas</a>
    <a href="#bonecos">Bonecos</a>
  </nav>
  <section class="produtos" id="camisas">
    <div class="produto">
      <img src="https://via.placeholder.com/300x300" alt="Camisa JMZIN">
      <h2>Camisa JMZIN</h2>
      <p>Estampa exclusiva do JMZIN. Tecido 100% algodão. Disponível nos tamanhos P, M, G e GG.</p>
    </div>
  </section>
  <section class="produtos" id="faixas">
    <div class="produto">
      <img src="https://via.placeholder.com/300x300" alt="Faixa JMZIN">
      <h2>Faixa JMZIN</h2>
      <p>Use no estilo JMZIN! Faixa estilosa com a marca registrada do canal. Tecido elástico e confortável.</p>
    </div>
  </section>
  <section class="produtos" id="bonecos">
    <div class="produto">
      <img src="https://via.placeholder.com/300x300" alt="Boneco JMZIN">
      <h2>Boneco JMZIN</h2>
      <p>Boneco colecionável do JMZIN! Detalhes incríveis e acabamento de qualidade. Ideal para fãs.</p>
    </div>
  </section>
  <footer>
    <p>Contato: 13 99800-4549</p>
    <p>JMZIN &copy; Todos os direitos reservados</p>
  </footer>
</body>
</html>
