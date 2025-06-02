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
      background: #e8f5e9; /* verde muy claro */
      color: #1b5e20; /* verde oscuro */
    }
    header {
      background: #1b5e20; /* verde oscuro */
      color: white;
      text-align: center;
      padding: 20px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav {
      display: flex;
      justify-content: center;
      background: white;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 70px; /* justo debajo del header */
      z-index: 999;
    }
    nav a {
      color: #1b5e20;
      padding: 15px 25px;
      text-decoration: none;
      display: block;
      font-weight: bold;
      border-bottom: 3px solid transparent;
      transition: border-bottom 0.3s ease;
    }
    nav a:hover, nav a:focus {
      border-bottom: 3px solid #4caf50; /* verde más claro */
    }
    section {
      padding: 40px 20px;
      border-bottom: 1px solid #a5d6a7; /* verde suave */
      background: white;
      max-width: 1000px;
      margin: 20px auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(27,94,32,0.1);
    }
    h2 {
      text-align: center;
      color: #1b5e20;
    }
    .productos {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }
    .producto {
      background: #c8e6c9; /* verde claro */
      border-radius: 10px;
      padding: 20px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(27,94,32,0.2);
      color: #1b5e20;
      font-weight: 600;
      transition: background-color 0.3s ease;
    }
    .producto:hover {
      background-color: #a5d6a7; /* verde más intenso */
      cursor: pointer;
    }
    footer {
      background: #1b5e20;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    /* Responsive para móviles */
    @media (max-width: 600px) {
      nav {
        flex-wrap: wrap;
      }
      .productos {
        flex-direction: column;
        align-items: center;
      }
      .producto {
        width: 90%;
      }
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
