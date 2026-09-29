<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Guedes Store | Moda Masculina</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
      color: #111;
    }

    header {
      background: #111;
      color: white;
      padding: 25px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 30px;
      letter-spacing: 2px;
    }

    header p {
      margin-top: 8px;
      color: #ccc;
    }

    nav {
      background: #222;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 70px 20px;
      background: white;
    }

    .hero h2 {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 18px;
      color: #555;
      margin-bottom: 25px;
    }

    .botao {
      display: inline-block;
      background: #111;
      color: white;
      padding: 14px 25px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    }

    section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 28px;
    }

    .categorias {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
    }

    .categoria {
      background: #111;
      color: white;
      padding: 30px 15px;
      text-align: center;
      border-radius: 8px;
      font-weight: bold;
    }

    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .produto {
      background: white;
      padding: 25px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 3px 10px rgba(0,0,0,0.08);
    }

    .produto h3 {
      margin-bottom: 10px;
    }

    .preco {
      font-size: 20px;
      font-weight: bold;
      margin: 15px 0;
    }

    .sobre {
      background: white;
      border-radius: 10px;
      text-align: center;
      line-height: 1.7;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 30px;
    }

    .whatsapp {
      display: inline-block;
      margin-top: 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>

<body>

  <header>
    <h1>GUEDES STORE</h1>
    <p>Moda masculina</p>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#sobre">Sobre</a>
  </nav>

  <div class="hero" id="inicio">
    <h2>Seu estilo. Seu momento.</h2>

    <p>
      Peças masculinas selecionadas para deixar
      seu visual mais marcante.
    </p>

    <a class="botao" href="#produtos">VER PRODUTOS</a>
  </div>

  <section>
    <h2>Categorias</h2>

    <div class="categorias">
      <div class="categoria">CAMISETAS</div>
      <div class="categoria">CALÇAS</div>
      <div class="categoria">SHORTS</div>
      <div class="categoria">ACESSÓRIOS</div>
    </div>
  </section>

  <section id="produtos">
    <h2>Destaques</h2>

    <div class="produtos">

      <div class="produto">
        <h3>Camiseta Premium</h3>
        <p>Modelo masculino premium.</p>
        <div class="preco">R$ 79,90</div>
        <a class="botao" href="https://wa.me/5516994049604">
          Comprar
        </a>
      </div>

      <div class="produto">
        <h3>Camiseta Oversized</h3>
        <p>Estilo moderno e confortável.</p>
        <div class="preco">R$ 89,90</div>
        <a class="botao" href="https://wa.me/5516994049604">
          Comprar
        </a>
      </div>

      <div class="produto">
        <h3>Calça Masculina</h3>
        <p>Versátil para diferentes ocasiões.</p>
        <div class="preco">R$ 129,90</div>
        <a class="botao" href="https://wa.me/5516994049604">
          Comprar
        </a>
      </div>

      <div class="produto">
        <h3>Shorts Casual</h3>
        <p>Conforto para o dia a dia.</p>
        <div class="preco">R$ 69,90</div>
        <a class="botao" href="https://wa.me/5516994049604">
          Comprar
        </a>
      </div>

    </div>
  </section>

  <section id="sobre">
    <div class="sobre">
      <h2>Sobre a Guedes Store</h2>

      <p>
        A Guedes Store é uma loja de moda masculina
        criada para quem busca estilo, praticidade e
        peças que combinam com diferentes momentos.
      </p>
    </div>
  </section>

  <footer>
    <h3>GUEDES STORE</h3>

    <p>Moda masculina • Instagram • WhatsApp</p>

    <a class="whatsapp" href="https://wa.me/5516994049604">
      Fale conosco pelo WhatsApp
    </a>

    <p style="margin-top:20px;">
      © 2026 Guedes Store. Todos os direitos reservados.
    </p>
  </footer>

</body>
</html>