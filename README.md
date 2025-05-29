# EL-URUNDAY-MIEL
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>elUrundai miel</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #fffaf0;
      color: #4b3d2a;
    }

    header {
      background-color: #f6e1a7;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      color: #a86b00;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    .section h2 {
      font-size: 2rem;
      color: #a86b00;
      margin-bottom: 1rem;
    }

    .section p, .section li {
      font-size: 1.2rem;
      line-height: 1.6;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }

    .product-card {
      background-color: #fff7df;
      border: 1px solid #e0c38c;
      padding: 1.5rem;
      border-radius: 10px;
      width: 260px;
      text-align: center;
    }

    .product-card img {
      max-width: 100%;
      border-radius: 8px;
    }

    .product-card h3 {
      margin-top: 1rem;
      color: #a86b00;
    }

    a.button {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.8rem 1.5rem;
      background-color: #a86b00;
      color: #fff;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background-color: #f6e1a7;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #5e4a2f;
    }
  </style>
</head>
<body>

  <header>
    <h1>elUrundai miel</h1>
    <p>Una dulzura natural que conecta con la tierra 🍯</p>
  </header>

  <section class="section">
    <h2>¿Quiénes somos?</h2>
    <p>Somos pequeños productores apasionados por las abejas, la naturaleza y el poder de lo auténtico. Cada frasco de miel es un homenaje al trabajo incansable de nuestras colmenas en la región del Urunday.</p>
  </section>

  <section class="section">
    <h2>Productos</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1560807707-8cc77767d783" alt="Frasco de miel 500g">
        <h3>Frasco 500g</h3>
        <p><strong>$4500</strong></p>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1615485927975-cb76d9e90d8c" alt="Frasco de miel 1kg">
        <h3>Frasco 1kg</h3>
        <p><strong>$8000</strong></p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>Contacto</h2>
    <p>¿Querés hacer un pedido, consultar o simplemente charlar sobre abejas?</p>
    <a href="https://atom.bio/urundayapicultura" target="_blank" class="button">Ir a nuestro contacto</a>
  </section>

  <footer>
    <p>© 2025 elUrundai miel. Hecho con amor, abejas y algo de sarcasmo.</p>
  </footer>

</body>
</html>
