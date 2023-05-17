# Projecte_Practic
Projecte de HTML5 / CSS3 del curs de openwebinars
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <title>Projecte Practic</title>
  <link rel="stylesheet" href="estilos.css">
  <style>
    html, body {
  margin: 0;
  padding: 0;
}
.background-image {
  background-color: #ffffff;
  background-image: url(../VisualEstudioProjecte/Captura\ de\ pantalla\ 2023-05-11\ 113036.png);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  width: 100%;
  height: 100vh;
}
.content {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.text-box {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: #003363;
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  padding-left: 20px;
}

.text {
  color: #ff80bf;
  font-size: 24px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  padding-left: 20px;
}

.button {
  background-color: #ff80bf;
  color: #ffffff;
  border: none;
  border-radius: 10px;
  padding: 10px 20px;
  font-size: 18px;
  margin-top: 10px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  padding-left: 20px;
}
.line {
  width: 200px;
  height: 3px;
  background-color: #ff80bf;
  position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  margin-top: 5px;
}
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 80px;
  background-color: #003363;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  padding-left: 20px;
}
ul {
  list-style: none;
 
display: flex;
  padding: 0;
  margin: 0;
}

li {
  margin-right: 20px;
  font-size: 22px;
  color:rgb(248, 70, 100);
}

a { 
text-decoration: none;
  color: #ff80bf;
  margin-left: 10px;
  font-smooth: never;
  -webkit-font-smoothing: none;
}
.section {
  display: flex;
  align-items: center;
  margin-top: 50px;
}

.left-image {
  width: 700px; 
  height: 700px;
}

.text-container {
  font-size: 16px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.text-container dt {
  font-weight: bold;
  margin-top: 5px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.text-container dd {
  margin: 5px 0;
}
.card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    
    .card {
      margin-top: 20px;
      width: 300px;
      border: none;
      border-radius: 5px;
      padding: 20px;
      text-align: center;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    
    .card img {
      width: 100%;
    }
    
    .card-text {
      margin-top: 10px;
      font-weight: bold;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
      color:#003363; 
    }
.container {
  display: flex;
  align-items: center;
  }
  .gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.image {
  transition: transform 0.3s;
}

.image:hover {
  transform: scale(1.1);
}
.row {
  display: flex;
}

img {
  width: 200px;
  height: 200px;
  margin-right: 10px;
  margin-bottom: 10px;
}
footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #003363;
  color: #ff80bf;
  padding: 10px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.footer-left {
      flex-grow: 1;
    }
    
    .footer-center {
      flex-grow: 2;
      text-align: center;
    }
    
    .footer-right {
      display: flex;
      gap: 10px;
    }
    
    .footer-right i {
      font-size: 24px;
    }

.footer-left, .footer-center, .footer-right {
  flex: 1;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.footer-right {
  display: flex;
  justify-content: flex-end;
  gap: 10px;
}
.footer-right i {
      font-size: 24px;
    }
.footer-right a {
  margin-left: 10px;
  color: #ff80bf;
  text-decoration: none;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.footer-right a:hover {
  color: white;
}
.line-pink {
  background-color: pink;
  height: 2px;
  width: 30%;
  margin: auto; 
}
@media (max-width: 767px) {
}
@media (min-width: 768px) and (max-width: 1023px) {
}
@media (min-width: 1024px) {
}

  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li>Inicio</li>
        <li>Producto</li>
        <li>Sobre nosotros</li>
        <li>Contactanos</li>
      </ul>
    </nav>
    </header>
    <div class="background-image"></div>
    <div class="content">
        <div class="text-box">
          <p class="text"> Si estas interesado</p>
          <button class="button">Comprar</button>
        </div>
      </div>
    </div>

    <hr class="line-pink">
<div class="card-container">
  <div class="card">
    <img src="../VisualEstudioProjecte/ff80808165ffc80e01660abec89e00c1-large.png" class="image">
    <p class="card-text">Directamente a tu Oficina</p>
  </div>
  <div class="card">
    <img src="../VisualEstudioProjecte/ff80808165ffc80e01660abec89e00c1-large.png" class="image">
    <p class="card-text">En caso de necesidad</p>
  </div>
  <div class="card">
    <img src="../VisualEstudioProjecte/ff80808165ffc80e01660abec89e00c1-large.png" class="image">
    <p class="card-text">Para saciar tu Sed</p>
  </div>
</div>
<hr class="line-pink">
<div class="section">
  <div class="container">
  <img src="../VisualEstudioProjecte/gallery.png" width="300px" alt="300px" class="left-image">
  <dl class="text-container">
    <dt>Texto de ejemplo 1:</dt>
    <dd>Textoejemplotextoejemplotextoejemplo<br>Textoejemplotextoejemp<br>lotextoejemploTextoejemplotextoejemplotextoejemplo
      Textoejemplo<br>textoejemplotextoejemploTextoejemplotextoejemplo<br>textoe<br>jemploTextoejemplotextoejemplotextoejemploTextoejemplo<br>textoejemplotextoejemplo
    </dd>
    <dt>Texto de ejemplo 2:</dt>
    <dd>Textoejemplotextoejemplotextoejemplo<br>Textoejemplotextoejemplotextoejemplo<br>Textoejemplotextoejemplotextoejemplo
      Textoejemplo<br>textoejemplotextoejemploTextoejemplotextoejemplo<br>textoejemploTextoejemplotextoejemplo<br>textoejemploTextoejemplo<br>textoejemplotextoejemplo
    </dd>
    <dt>Texto de ejemplo 3:</dt>
    <dd>Textoejemplotextoejemplotextoejemplo<br>Textoejemplotextoejemplotextoejemplo<br>Textoejemplotextoejemplotextoejemplo
      Textoejemplotextoejemplo<br>textoejemploTextoejemplo<br>textoejemplo<br>textoejemploTextoejemplotextoejemplo<br>textoejemploTextoejemplo<br>textoejemplotextoejemplo
   </dd>
  </dl>
</div>
</div>
<div class="gallery">
  <div class="row">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
  </div>
  <div class="row">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
    <img src="../VisualEstudioProjecte/gallery.png" class="image">
  </div>
</div>
<footer>
  <div class="footer-left">
    <p>Calle Virgen del Valle 2A<br>41011 Sevilla</p>
  </div>
  <div class="footer-center">
    <p>Copyright 2018 Todos los derechos reservados</p>
  </div>
  <div class="footer-right">
    <i class="fab fa-instagram" ></i>
    <i class="fab fa-youtube" ></i>
    <i class="fab fa-facebook"></i>
  </div>
</footer>

</body>

</html>
