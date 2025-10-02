<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Loja</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #222; color: white; padding: 1rem; text-align: center; }
    .produtos { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; padding: 1rem; }
    .card { border: 1px solid #ddd; border-radius: 10px; padding: 1rem; text-align: center; }
    .card img { width: 100%; border-radius: 10px; }
    .whats { background: #25D366; color: white; padding: 10px; border-radius: 5px; text-decoration: none; display: inline-block; margin-top: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Minha Loja Online</h1>
    <p>Entre em contato pelo WhatsApp para comprar!</p>
  </header>

  <main class="produtos">
    <div class="card">
      <img src="https://via.placeholder.com/200" alt="Produto 1">
      <h2>Produto 1</h2>
      <p>R$ 100,00</p>
      <a class="whats" href="https://wa.me/5599999999999" target="_blank">Comprar no WhatsApp</a>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/200" alt="Produto 2">
      <h2>Produto 2</h2>
      <p>R$ 150,00</p>
      <a class="whats" href="https://wa.me/5599999999999" target="_blank">Comprar no WhatsApp</a>
    </div>
  </main>
</body>
</html>

