 <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gangas Uruguay</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background-color: #f8f8f8;
      color: #222;
    }
    header {
      background-color: #c40000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 80px;
    }
    h1 {
      margin: 10px 0 0;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }
    .producto {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      width: 220px;
      text-align: center;
      padding: 15px;
    }
    .producto img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 5px;
    }
    .producto h3 {
      margin: 10px 0 5px;
    }
    .producto p {
      margin: 0;
      color: #c40000;
      font-weight: bold;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px;
    }
    .whatsapp {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 15px;
      margin-top: 15px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo Gangas Uruguay" />
    <h1>Gangas Uruguay</h1>
    <p>Las mejores ofertas de segunda mano en un solo lugar</p>
  </header>

  <section class="productos">
    <div class="producto">
      <img src="https://via.placeholder.com/200x180.png?text=Producto+1" alt="Producto 1" />
      <h3>Smart TV 50"</h3>
      <p>$12.500</p>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/200x180.png?text=Producto+2" alt="Producto 2" />
      <h3>Heladera Whirlpool</h3>
      <p>$8.900</p>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/200x180.png?text=Producto+3" alt="Producto 3" />
      <h3>Bicicleta GT</h3>
      <p>$5.500</p>
    </div>
  </section>

  <footer>
    <p>Contacto por WhatsApp</p>
    <a class="whatsapp" href="https://wa.me/59897213277" target="_blank">📲 097 213 277</a>
    <p>&copy; 2025 Gangas Uruguay</p>
  </footer>
</body>
</html>
