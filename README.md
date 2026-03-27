# KCPKartingOutdoorPY.com
Alquiler y Centro de eventos de Karting en el Comite Olímpico Paraguayo 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KCP Karting Outdoor</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: #0b0f1a;
  color: white;
}

/* HERO */
.hero {
  height: 100vh;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.8)),
  url('https://images.unsplash.com/photo-1549921296-3a6b9f56e41b') center/cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  opacity: 0.8;
}

.btn {
  margin-top: 20px;
  padding: 15px 30px;
  background: #22c55e;
  color: black;
  text-decoration: none;
  border-radius: 10px;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #16a34a;
}

/* SECCIONES */
section {
  padding: 60px 20px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  margin-bottom: 20px;
  font-size: 2rem;
}

/* CARDS */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #111827;
  padding: 20px;
  border-radius: 12px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: #020617;
  color: gray;
}
</style>
</head>

<body>

<div class="hero">
  <h1>KCP Karting Outdoor</h1>
  <p>Velocidad, adrenalina y diversión al máximo nivel</p>
  <a href="#contacto" class="btn">Reservar ahora</a>
</div>

<section>
  <h2>🏎️ Experiencia</h2>
  <div class="cards">
    <div class="card">
      <h3>Pista profesional</h3>
      <p>Circuito bien mantenido para una experiencia real de competición.</p>
    </div>
    <div class="card">
      <h3>Karts de calidad</h3>
      <p>Vehículos seguros, rápidos y en excelente estado.</p>
    </div>
    <div class="card">
      <h3>Seguridad</h3>
      <p>Instalaciones amplias y personal profesional.</p>
    </div>
  </div>
</section>

<section>
  <h2>⭐ Opiniones</h2>
  <p><strong>4.5 / 5</strong> ⭐ (687 reseñas)</p>
  <p>
    Los visitantes destacan la experiencia divertida y emocionante,
    la pista bien cuidada y el excelente servicio.
  </p>
</section>

<section>
  <h2>💰 Precios</h2>
  <div class="cards">
    <div class="card">
      <h3>Sesión individual</h3>
      <p>$10 - $20</p>
    </div>
    <div class="card">
      <h3>Grupos</h3>
      <p>Descuentos para amigos y eventos</p>
    </div>
    <div class="card">
      <h3>Eventos</h3>
      <p>Cumpleaños y celebraciones</p>
    </div>
  </div>
</section>

<section id="contacto">
  <h2>📍 Contacto</h2>
  <p>📞 +595 976 330666</p>
  <p>📧 info@kcpkarting.com</p>
  <p>📍 Asuncíon, Luque</p>
</section>

<footer>
  © 2026 KCP Karting Outdoor
</footer>

</body>
</html>
