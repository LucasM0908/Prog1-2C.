<html>
<head>
  <title>Torregamaes - Venda de Key de Jogos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
    }

    .container {
      width: 80%;
      margin: 0 auto;
    }

    .logo {
      text-align: center;
      margin-top: 20px;
    }

    .logo img {
      width: 300px;
    }

    .menu {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin-top: 20px;
    }

    .menu a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    .menu a:hover {
      color: #666;
    }

    .content {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      grid-gap: 20px;
      margin-top: 20px;
    }

    .card {
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card h3 {
      text-align: center;
      margin: 10px 0;
    }

    .card p {
      text-align: center;
      color: #333;
      font-weight: bold;
    }

    .card button {
      display: block;
      width: 80%;
      margin: 10px auto;
      padding: 10px;
      border: none;
      border-radius: 10px;
      background-color: #333;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
    }

    .card button:hover {
      background-color: #666;
    }

    .footer {
      text-align: center;
      margin-top: 20px;
      margin-bottom: 20px;
      color: #333;
    }

    .footer a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    .footer a:hover {
      color: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo">
      <img src="logo.png" alt="Logo do Torregamaes">
    </div>
    <div class="menu">
      <a href="#">Início</a>
      <a href="#">Plataformas</a>
      <a href="#">Gêneros</a>
      <a href="#">Contato</a>
    </div>
    <div class="content">
      <div class="card">
        <img src="gta5.jpg" alt="GTA 5">
        <h3>GTA 5</h3>
        <p>R$ 49,90</p>
        <button onclick="buy('GTA 5', '49.90')">Comprar</button>
      </div>
      <div class="card">
        <img src="minecraft.jpg" alt="Minecraft">
        <h3>Minecraft</h3>
        <p>R$ 29,90</p>
        <button onclick="buy('Minecraft', '29.90')">Comprar</button>
      </div>
      <div class="card">
        <img src="fifa21.jpg" alt="FIFA 21">
        <h3>FIFA 21</h3>
        <p>R$ 99,90</p>
        <button onclick="buy('FIFA 21', '99.90')">Comprar</button>
      </div>
      <div class="card">
        <img src="cyberpunk2077.jpg" alt="Cyberpunk 2077">
        <h3>Cyberpunk 2077</h3>
        <p>R$ 199,90</p>
        <button onclick="buy('Cyberpunk 2077', '199.90')">Comprar</button>
      </div>
    </div>
    <div class="footer">
      <p>Todos os direitos reservados © Torregamaes 2024</p>
      <p>Formas de pagamento: PIX ou Cartão</p>
      <a href="#">Política de privacidade</a> | <a href="#">Termos de uso</a>
    </div>
  </div>
  <script>
    function buy(game, price) {
      // Essa função é apenas um exemplo e não faz o pagamento ou a entrega da Key de verdade
      // Você pode usar uma API de pagamento como o Mercado Pago ou o PagSeguro para integrar o seu site
      // Você também pode usar um serviço de email como o SendGrid ou o Mailgun para enviar a Key para o cliente
      alert("Você comprou o jogo " + game + " por R$ " + price + ". A Key será enviada para o seu email em breve.");
    }
  </script>
</body>
</html>
