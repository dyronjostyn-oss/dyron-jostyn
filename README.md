<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BELA AFRODITE 5 | Spa & Salón de Cosmetología</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#fff;
    color:#222;
}

header{
    background:#000;
    color:#fff;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:32px;
    font-weight:bold;
    letter-spacing:2px;
}

.logo span{
    color:#d4af37;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1515377905703-c4788e51af15');
    background-size:cover;
    background-position:center;
    color:white;
    text-align:center;
    padding:120px 20px;
}

.hero h1{
    font-size:55px;
}

.hero p{
    margin-top:15px;
    font-size:20px;
}

.btn{
    display:inline-block;
    margin-top:25px;
    background:#d4af37;
    color:black;
    padding:15px 30px;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

section{
    padding:70px 8%;
}

.titulo{
    text-align:center;
    margin-bottom:40px;
    font-size:35px;
}

.servicios{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#f5f5f5;
    padding:25px;
    border-radius:15px;
    text-align:center;
}

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}

.galeria img{
    width:100%;
    border-radius:12px;
}

.promos{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.promo{
    background:black;
    color:white;
    padding:30px;
    border-radius:15px;
    text-align:center;
}

.owner{
    background:#f5f5f5;
    text-align:center;
}

.owner h3{
    color:#d4af37;
    margin-top:10px;
}

.contacto form{
    max-width:600px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:15px;
    margin-bottom:15px;
    border:1px solid #ccc;
    border-radius:10px;
}

button{
    background:#d4af37;
    border:none;
    padding:15px 30px;
    border-radius:30px;
    cursor:pointer;
    font-weight:bold;
}

footer{
    background:black;
    color:white;
    text-align:center;
    padding:25px;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}
</style>
</head>

<body>

<header>
<div class="logo">BELA <span>AFRODITE 5</span></div>

<nav>
<a href="#servicios">Servicios</a>
<a href="#galeria">Galería</a>
<a href="#promociones">Promociones</a>
<a href="#contacto">Contacto</a>
</nav>
</header>

<section class="hero">
<h1>BELA AFRODITE 5</h1>
<p>Spa & Salón de Cosmetología</p>
<p>Tu belleza y bienestar son nuestra prioridad.</p>

<a class="btn"
href="https://wa.me/51999999999?text=Hola,%20quiero%20reservar%20una%20cita">
Reservar por WhatsApp
</a>
</section>

<section class="owner">
<h2 class="titulo">Propietario</h2>
<h3>Evolet Córdoba Delgado</h3>
<p>Fundador y Director General de BELA AFRODITE 5</p>
</section>

<section id="servicios">
<h2 class="titulo">Nuestros Servicios</h2>

<div class="servicios">

<div class="card">
<h3>Cosmetología Facial</h3>
<p>Limpieza facial profunda y tratamientos rejuvenecedores.</p>
</div>

<div class="card">
<h3>Spa Relajante</h3>
<p>Masajes, aromaterapia y bienestar integral.</p>
</div>

<div class="card">
<h3>Belleza Integral</h3>
<p>Maquillaje, cejas, pestañas y cuidado personal.</p>
</div>

<div class="card">
<h3>Manicure & Pedicure</h3>
<p>Tratamientos estéticos para manos y pies.</p>
</div>

</div>
</section>

<section id="galeria">
<h2 class="titulo">Galería de Servicios</h2>

<div class="galeria">
<img src="https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f">
<img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2">
<img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15">
<img src="https://images.unsplash.com/photo-1519415943484-9fa1873496d4">
</div>
</section>

<section id="promociones">
<h2 class="titulo">Promociones</h2>

<div class="promos">

<div class="promo">
<h3>20% OFF</h3>
<p>Limpieza Facial</p>
</div>

<div class="promo">
<h3>25% OFF</h3>
<p>Masajes Relajantes</p>
</div>

<div class="promo">
<h3>30% OFF</h3>
<p>Paquete Spa + Facial</p>
</div>

</div>
</section>

<section id="contacto" class="contacto">
<h2 class="titulo">Contáctanos</h2>

<form onsubmit="enviarFormulario(event)">
<input type="text" placeholder="Nombre" required>
<input type="email" placeholder="Correo electrónico" required>
<textarea rows="5" placeholder="Mensaje"></textarea>

<button type="submit">Enviar</button>
</form>
</section>

<footer>
<p>© 2026 BELA AFRODITE 5</p>
<p>Propietario: Evolet Córdoba Delgado</p>
</footer>

<a class="whatsapp"
href="https://wa.me/51965457 498?text=Hola,%20quiero%20información">
WhatsApp
</a>

<script>
function enviarFormulario(e){
e.preventDefault();
alert("Mensaje enviado correctamente.");
}
</script>

</body>
</html>
