<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>el Urunday Miel</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #fffaf1;
      color: #4b3d2a;
      line-height: 1.6;
    }

    header {
      background-color: #f3e1a7;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      color: #a86b00;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    section {
      max-width: 1000px;
      margin: 3rem auto;
      padding: 0 2rem;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #a86b00;
    }

    .productos {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }

    .producto {
      background: #fff8e6;
      border: 1px solid #e4c999;
      padding: 1rem;
      border-radius: 10px;
      text-align: center;
      width: 260px;
    }

    .producto img {
      width: 100%;
      border-radius: 8px;
    }

    .producto h3 {
      margin: 1rem 0 0.5rem;
      color: #a86b00;
    }

    .boton {
      display: inline-block;
      background-color: #a86b00;
      color: white;
      padding: 0.8rem 1.5rem;
      margin-top: 2rem;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    footer {
      background: #f3e1a7;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>el Urunday miel</h1>
    <p>Miel 100% natural. De nuestras abejas, directo a tu mesa.</p>
  </header>

  <section>
    <h2>Nuestros productos</h2>
    <div class="productos">
      <div class="producto">
        <img src="https://images.unsplash.com/photo-1560807707-8cc77767d783" alt="Miel 500g">
        <h3>Frasco 500g</h3>
        <p>$4500</p>
      </div>
      <div class="producto">
        <img src="https://images.unsplash.com/photo-1615485927975-cb76d9e90d8c" alt="Miel 1kg">
        <h3>Frasco 1kg</h3>
        <p>$8000</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Por qué elegirnos</h2>
    <p>
      Cultivamos miel de forma artesanal, cuidando a cada abeja como si fuera familia. El Urunday no es solo un nombre: es nuestra tierra, nuestras flores y nuestra historia embotellada en cada frasco.
    </p>
  </section>

  <section>
    <h2>Contacto</h2>
    <p>¿Querés hacer un pedido o hablar con nosotros?</p>
    <a href="https://www.atom.bio/urundayapicultura" class="boton" target="_blank">Ir al contacto</a>
  </section>

  <footer>
    <p>© 2025 el Urunday miel. Hecho con amor, abejas y dulzura salvaje.</p>
  </footer>
</body>
</html>
