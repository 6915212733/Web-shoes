<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tienda de Zapatillas</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #333;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #575757;
    }
    section {
      padding: 40px;
      border-bottom: 1px solid #ccc;
      background: white;
    }
    h2 {
      text-align: center;
      color: #222;
    }
    .productos {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }
    .producto {
      background: #eee;
      border-radius: 10px;
      padding: 20px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Tienda de Zapatillas</h1>
  <p>Explorá nuestras categorías</p>
</header>

<nav>
  <a href="#deportivas">Deportivas</a>
  <a href="#urbanas">Urbanas</a>
  <a href="#running">Running</a>
  <a href="#exclusivas">Exclusivas</a>
  <a href="#ofertas">Ofertas</a>
</nav>

<section id="deportivas">
  <h2>Zapatillas Deportivas</h2>
  <div class="productos">
    <div class="producto">Nike Air Zoom</div>
    <div class="producto">Adidas Ultraboost</div>
    <div class="producto">Puma Ignite</div>
  </div>
</section>

<section id="urbanas">
  <h2>Zapatillas Urbanas</h2>
  <div class="productos">
    <div class="producto">Converse Chuck Taylor</div>
    <div class="producto">Nike Blazer Mid</div>
    <div class="producto">Vans Old Skool</div>
  </div>
</section>

<section id="running">
  <h2>Zapatillas Running</h2>
  <div class="productos">
    <div class="producto">Asics Gel Nimbus</div>
    <div class="producto">New Balance 1080</div>
    <div class="producto">Brooks Ghost</div>
  </div>
</section>

<section id="exclusivas">
  <h2>Zapatillas Exclusivas</h2>
  <div class="productos">
    <div class="producto">Yeezy Boost 350</div>
    <div class="producto">Air Jordan 1 Retro</div>
    <div class="producto">Balenciaga Triple S</div>
  </div>
</section>

<section id="ofertas">
  <h2>Ofertas</h2>
  <div class="productos">
    <div class="producto">Nike Downshifter -30%</div>
    <div class="producto">Reebok Classic -25%</div>
    <div class="producto">Fila Disruptor -40%</div>
  </div>
</section>

<footer>
  <p>&copy; 2025 Tienda de Zapatillas. Todos los derechos reservados.</p>
</footer>

</body>
</html>
