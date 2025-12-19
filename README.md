# Pacotes-posts
Site para venda de pacotes de posts para Instagram
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pacotes de Posts Prontos</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(90deg, #6a11cb, #2575fc);
      color: #fff;
      padding: 50px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.8em;
      margin-bottom: 15px;
    }
    header p {
      font-size: 1.2em;
    }
    header .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 35px;
      background-color: #ff6a00;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      transition: all 0.3s;
    }
    header .btn:hover {
      background-color: #ff3d00;
      transform: scale(1.05);
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 50px;
      font-size: 2.2em;
      color: #2575fc;
    }

    /* Pacotes */
    .packages {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }
    .package-card {
      background-color: #fff;
      padding: 30px 20px;
      border-radius: 20px;
      box-shadow: 0 7px 20px rgba(0,0,0,0.12);
      width: 250px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .package-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 25px rgba(0,0,0,0.2);
    }
    .package-card img {
      width: 90px;
      margin-bottom: 20px;
      transition: transform 0.3s;
    }
    .package-card:hover img {
      transform: rotate(10deg);
    }
    .package-card h3 {
      margin-bottom: 10px;
      color: #6a11cb;
    }
    .package-card p {
      font-size: 0.95em;
      margin-bottom: 20px;
    }
    .package-card .btn {
      background-color: #2575fc;
      transition: background 0.3s, transform 0.3s;
    }
    .package-card .btn:hover {
      background-color: #6a11cb;
      transform: scale(1.05);
    }

    /* Como funciona */
    .steps {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .step {
      background-color: #fff;
      padding: 25px;
      border-radius: 20px;
      width: 220px;
      text-align: center;
      box-shadow: 0 7px 20px rgba(0,0,0,0.12);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .step:hover {
      transform: translateY(-8px);
      box-shadow: 0 12px 25px rgba(0,0,0,0.18);
    }
    .step h4 {
      margin: 15px 0 10px;
      color: #ff6a00;
    }

    /* Contato */
    .contact-form {
      background-color: #fff;
      padding: 45px;
      border-radius: 20px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 7px 20px rgba(0,0,0,0.12);
    }
    .contact-form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 20px;
      border-radius: 8px;
      border: 1px solid #ccc;
      transition: border 0.3s;
    }
    .contact-form input:focus,
    .contact-form textarea:focus {
      border: 2px solid #2575fc;
      outline: none;
    }
    .contact-form button {
      background-color: #ff6a00;
      color: #fff;
      border: none;
      padding: 16px 30px;
      border-radius: 30px;
      cursor: pointer;
      transition: background 0.3s, transform 0.3s;
    }
    .contact-form button:hover {
      background-color: #ff3d00;
      transform: scale(1.05);
    }

    /* Rodapé */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 25px 20px;
    }
    footer a {
      color: #ff6a00;
      text-decoration: none;
      margin: 0 10px;
    }
    footer a:hover {
      text-decoration: underline;
    }

    /* Responsivo */
    @media (max-width: 768px) {
      .packages, .steps {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Pacotes de Posts Prontos</h1>
    <p>Conteúdos prontos e estratégicos para redes sociais de diversos segmentos</p>
    <a href="#pacotes" class="btn">Ver Pacotes</a>
  </header>

  <!-- Pacotes -->
  <section id="pacotes">
    <h2>Nossos Pacotes</h2>
    <div class="packages">
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/dog.png" alt="Petshop">
        <h3>Petshop</h3>
        <p>Posts estratégicos para aumentar o engajamento do seu petshop.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Petshop" class="btn" target="_blank">Quero este pacote</a>
      </div>
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/barber-shop.png" alt="Barbearia">
        <h3>Barbearia</h3>
        <p>Posts criativos para atrair clientes e destacar sua barbearia.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Barbearia" class="btn" target="_blank">Quero este pacote</a>
      </div>
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/restaurant.png" alt="Restaurante">
        <h3>Restaurante</h3>
        <p>Posts planejados para engajar seguidores e aumentar pedidos.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Restaurante" class="btn" target="_blank">Quero este pacote</a>
      </div>
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/dumbbell.png" alt="Academia">
        <h3>Academia</h3>
        <p>Posts motivacionais e promocionais para atrair mais alunos.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Academia" class="btn" target="_blank">Quero este pacote</a>
      </div>
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/hairdresser.png" alt="Salão">
        <h3>Salão de Beleza</h3>
        <p>Posts para mostrar serviços e atrair novos clientes.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Sal%C3%A3o" class="btn" target="_blank">Quero este pacote</a>
      </div>
      <div class="package-card">
        <img src="https://img.icons8.com/color/96/000000/t-shirt.png" alt="Loja de Roupas">
        <h3>Loja de Roupas</h3>
        <p>Posts para divulgar produtos e promoções de forma criativa.</p>
        <a href="https://wa.me/5511999999999?text=Quero%20o%20pacote%20Loja%20de%20Roupas" class="btn" target="_blank">Quero este pacote</a>
      </div>
    </div>
  </section>

  <!-- Como funciona -->
  <section id="como-funciona">
    <h2>Como Funciona</h2>
    <div class="steps">
      <div class="step">
        <img src="https://img.icons8.com/color/96/000000/idea.png" alt="Escolha">
        <h4>1. Escolha</h4>
        <p>Escolha o segmento e o pacote ideal para seu negócio.</p>
      </div>
      <div class="step">
        <img src="https://img.icons8.com/color/96/000000/delivery.png" alt="Receba">
        <h4>2. Receba</h4>
        <p>Receba os posts prontos em arquivos editáveis para suas redes.</p>
      </div>
      <div class="step">
        <img src="https://img.icons8.com/color/96/000000/growth.png" alt="Publique">
        <h4>3. Publique</h4>
        <p>Publique e aumente o engajamento do seu negócio!</p>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato">
    <h2>Contato</h2>
    <div class="contact-form">
      <form>
        <label for="nome">Nome</label>
        <input type="text" id="nome" name="nome" required>
        <label for="email">E-mail</label>
        <input type="email" id="email" name="email" required>
        <label for="whatsapp">WhatsApp</label>
        <input type="text" id="whatsapp" name="whatsapp" required>
        <label for="mensagem">Mensagem</label>
        <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
        <button type="submit">Quero meu pacote</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2025 Pacotes de Posts Prontos | Redes sociais: 
      <a href="https://instagram.com/" target="_blank">Instagram</a> | 
      <a href="https://wa.me/5511999999999" target="_blank">WhatsApp</a>
    </p>
  </footer>

</body>
</html>