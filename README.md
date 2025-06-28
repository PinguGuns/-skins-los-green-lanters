# -skins-los-green-lanters
armas skins
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda de Skins</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #1a1a1a;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background: #222;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #f39c12;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: #333;
      padding: 15px;
      border-radius: 8px;
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 5px;
    }
    .price {
      color: #f39c12;
      font-weight: bold;
      margin: 10px 0;
    }
    button {
      background: #f39c12;
      border: none;
      padding: 10px 20px;
      color: #000;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #222;
      padding: 10px;
      text-align: center;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda de Skins de Armas</h1>
    <p>¡Compra los mejores skins para tus armas favoritas!</p>
  </header>

  <div class="container">
    <div class="card">
      <img src="C:\Users\david\Downloads\image.webp" alt="Cuchillo Táctico">
      <h3>Cuchillo Táctico</h3>
      <div class="price">$3</div>
      <button>Comprar</button>
    </div>

    <div class="card">
      <img src="C:\Users\david\Downloads\pc.png" alt="Pistola de Combate">
      <h3>Pistola de Combate</h3>
      <div class="price">$5</div>
      <button>Comprar</button>
    </div>
  </div>

  <footer>
    &copy; 2025 Tienda de Skins. Todos los derechos reservados.
  </footer>
</body>
</html>
