<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Promociones Nacionales</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <div class="container">
      <h1>Promociones Nacionales</h1>
      <nav>
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Promociones</a></li>
          <li><a href="#">Destinos</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="promo-grid">

      <div class="promo-card">
        <img src="img/cartagena.jpg" alt="Cartagena">
        <h2>Cartagena</h2>
        <p>Desde $500.000 COP</p>
        <a href="#">Ver más</a>
      </div>

      <div class="promo-card">
        <img src="img/sanandres.jpg" alt="San Andrés">
        <h2>San Andrés</h2>
        <p>Desde $650.000 COP</p>
        <a href="#">Ver más</a>
      </div>

      <div class="promo-card">
        <img src="img/santamarta.jpg" alt="Santa Marta">
        <h2>Santa Marta</h2>
        <p>Desde $480.000 COP</p>
        <a href="#">Ver más</a>
      </div>

      <!-- Puedes agregar más tarjetas aquí -->

    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; 2025 Tu Agencia de Viajes - Todos los derechos reservados.</p>
    </div>
  </footer>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

header {
  background: #003366;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  text-align: center;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

.promo-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  margin: 40px 0;
}

.promo-card {
  background: white;
  border: 1px solid #ccc;
  border-radius: 8px;
  overflow: hidden;
  width: 300px;
  text-align: center;
  transition: box-shadow 0.3s;
}

.promo-card:hover {
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.promo-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.promo-card h2 {
  margin: 15px 0 10px;
}

.promo-card p {
  color: #007BFF;
  font-weight: bold;
}

.promo-card a {
  display: inline-block;
  margin: 15px 0;
  padding: 10px 20px;
  background: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 4px;
}

footer {
  background: #003366;
  color: white;
  text-align: center;
  padding: 20px 0;
}
</body>
</html>
