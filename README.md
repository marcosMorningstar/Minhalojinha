<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TechLife</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }

    .produtos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }

    .produto {
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 15px;
      text-align: center;
      width: 200px;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    }

    .produto img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }

    .produto h3 {
      margin: 10px 0 5px;
    }

    .produto .preco {
      font-size: 18px;
      color: #333;
      margin-bottom: 10px;
    }

    .produto a {
      display: inline-block;
      background-color: #25D366;
      color: white;
      text-decoration: none;
      padding: 10px 15px;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    .produto a:hover {
      background-color: #1ebe5d;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>TechLife</h1>
    <p>Capinhas, fones e películas pra proteger seu estilo!</p>
  </header>

  <div class="produtos">
    <div class="produto">
      <img src="https://m.media-amazon.com/images/I/61ZxGqjvEQL._AC_SL1500_.jpg" alt="Capinha para iPhone">
      <h3>Capinha para iPhone</h3>
      <p class="preco">R$ 39,90</p>
      <a href="https://wa.me/5527995809583?text=Olá%2C%20tenho%20interesse%20na%20Capinha%20para%20iPhone" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="https://m.media-amazon.com/images/I/61B3P5ixl8L._AC_SL1000_.jpg" alt="Capinha para Android">
      <h3>Capinha para Android</h3>
      <p class="preco">R$ 29,90</p>
      <a href="https://wa.me/5527995809583?text=Olá%2C%20tenho%20interesse%20na%20Capinha%20para%20Android" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="https://m.media-amazon.com/images/I/51tJyz+XW9L._AC_SL1000_.jpg" alt="Fone de Ouvido Bluetooth">
      <h3>Fone de Ouvido Bluetooth</h3>
      <p class="preco">R$ 79,90</p>
      <a href="https://wa.me/5527995809583?text=Olá%2C%20tenho%20interesse%20no%20Fone%20de%20Ouvido%20Bluetooth" target="_blank">Comprar</a>
    </div>

    <div class="produto">
      <img src="https://m.media-amazon.com/images/I/71YIyz+RZ5L._AC_SL1500_.jpg" alt="Película de Vidro">
      <h3>Película de Vidro</h3>
      <p class="preco">R$ 19,90</p>
      <a href="https://wa.me/5527995809583?text=Olá%2C%20tenho%20interesse%20na%20Película%20de%20Vidro" target="_blank">Comprar</a>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 TechLife - Todos os direitos reservados</p>
  </footer>

</body>
</html>
