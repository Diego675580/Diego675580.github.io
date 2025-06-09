<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Landing Page - Produtos</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
      color: #111;
    }

    header {
      background-color: #000;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background-color: #f5f5f5;
      border: 1px solid #ccc;
      border-radius: 10px;
      overflow: hidden;
      text-align: center;
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card h2 {
      font-size: 1.25rem;
      margin: 1rem 0 0.5rem;
      color: #111;
    }

    .card p {
      padding: 0 1rem 1rem;
      font-size: 0.95rem;
      color: #444;
    }

    .card button {
      background-color: #000;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      margin-bottom: 1rem;
      cursor: pointer;
      border-radius: 6px;
      font-size: 1rem;
    }

    .card button:hover {
      background-color: #333;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background-color: #eee;
      color: #555;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Nossos Produto</h1>
    <p>Conheça nossas ofertas exclusivas</p>
  </header>

  <div class="container">
  <div class="card">
      <img src="https://imgnike-a.akamaihd.net/1920x1920/013702NXA1.jpg" alt="Produto 1">
      <h2>Produto 1</h2>
      <p>Descrição breve do produto 1. Excelente custo-benefício!</p>
      <button onclick="comprar('Produto 1')">Comprar</button>
    </div>
    <div class="card">
      <img src="https://imgnike-a.akamaihd.net/1920x1920/058760IDA1.jpg" alt="Produto 2">
      <h2>Produto 2</h2>
      <p>Produto de alta qualidade para suas necessidades diárias.</p>
      <button onclick="comprar('Produto 2')">Comprar</button>
    </div>
    <div class="card">
      <img src="https://imgnike-a.akamaihd.net/1920x1920/0266095CA8.jpg" alt="Produto 3">
      <h2>Produto 3</h2>
      <p>Solução inovadora e prática. Confira agora!</p>
      <button onclick="comprar('Produto 3')">Comprar</button>
  </div>
  </div>

  <footer>
    &copy; 2025 Sua Empresa. Todos os direitos reservados.
  </footer>

  <script>
    function comprar(produto) {
      alert(`Você clicou para comprar : ${produto}`);
    }
  </script>

</body>
</html>
