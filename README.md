<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="keyword" content="Nayeli Katerine Sucasaca Lope, Contabilidad, UCSP" />
  <title>Nayeli Katerine Sucasaca Lope</title>
  <style>
    body {
      background-color: #ffffff; 
      color: #4a148c;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #7b1fa2; 
      color: white;
      padding: 30px 20px;
      width: 100%;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    main {
      max-width: 900px;
      width: 90%;
      margin: 20px 0;
    }

    section {
      background-color: #f3e5f5; 
      border-left: 5px solid #9c27b0; 
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #4a148c;
      margin-top: 0;
    }

    p, li {
      line-height: 1.6;
      color: #311b92;
    }

    a {
      color: #7b1fa2;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: #4a148c;
      text-decoration: underline;
    }

    ul {
      list-style: square;
      padding-left: 20px;
    }

    /* Estilos para la imagen */
    .perfil-img {
      width: 180px; 
      height: 180px; 
      border-radius: 50%; 
      border: 5px solid #ffffff; 
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      margin-top: -90px; /* Sube la foto un poco sobre el header */
      background-color: white;
    }

    .img-container {
      text-align: center;
      width: 100%;
    }

    /* Dropdown */
    .dropdown {
      text-align: center;
    }

    .dropdown-btn {
      background-color: #9c27b0;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    .dropdown-btn:hover {
      background-color: #7b1fa2;
    }

    .dropdown-content {
      display: none;
      margin-top: 10px;
      background-color: #ffffff;
      border-radius: 6px;
      padding: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .dropdown-content a {
      display: block;
      padding: 8px;
      border-bottom: 1px solid #f3e5f5;
    }

    .show {
      display: block;
    }

    footer {
      background-color: #7b1fa2;
      color: white;
      text-align: center;
      padding: 20px 0;
      width: 100%;
      margin-top: auto;
    }
  </style>
</head>
<body>

  <header>
    <h1>Nayeli Katerine Sucasaca Lope</h1>
    <p>Estudiante de Contabilidad</p>
  </header>

  <div class="img-container">
    <img src="perfil.jfif.jfif" alt="Foto de Nayeli" class="perfil-img">
  </div>

  <main>
    <section id="biografia">
      <h2>Biografía</h2>
      <p>
        Hola, mi nombre es <strong>Nayeli Katerine Sucasaca Lope</strong>, estudiante de 
        <a href="https://ucsp.edu.pe/facultad-de-ciencias-economicas-y-empresariales/carrera-de-contabilidad/" target="_blank">Contabilidad</a> 
        en la <a href="https://ucsp.edu.pe/" target="_blank">Universidad Católica San Pablo (UCSP)</a> 
        de Arequipa, Perú. Tengo 20 años de edad.
      </p>
      <p>
        Me defino como una persona analítica y detallista, apasionada por las finanzas y la gestión empresarial como motores de crecimiento sólido. Mi objetivo es aplicar normativas y conocimientos técnicos en entornos reales, buscando siempre generar orden e impacto positivo en la estrategia corporativa.
      </p>
    </section>

    <section id="cursos">
      <h2>Cursos Actuales</h2>
      <ul>
        <li>Contabilidad III</li>
        <li>Legislación laboral</li>
        <li>Legislación y auditoría tributaria</li>
        <li>Cálculo en una variable</li>
        <li>Estadística y probabilidades</li>
        <li>Introducción a la computación</li>
      </ul>
    </section>

    <section id="docentes">
      <h2>Perfiles de mis docentes</h2>
      <ul>
        <li><strong>Contabilidad III:</strong> <a href="mailto:ggarciaj@ucsp.edu.pe">García Jarufe Giovanna María</a></li>
        <li><strong>Legislación Laboral:</strong> 
          <ul>
            <li>Abarca Rubianes Carlos Rodrigo (Adjunto)</li>
            <li><a href="mailto:ggarciaj@ucsp.edu.pe">García Jarufe Giovanna María</a> (Principal)</li>
          </ul>
        </li>
        <li><strong>Legislación y Auditoría Tributaria:</strong> Amat y León Arispe Juan Sebastian</li>
        <li><strong>Cálculo en una Variable:</strong> Rendón García Fiorella María</li>
        <li><strong>Estadística y Probabilidades:</strong> 
          <ul>
            <li>Enriquez Cáceres Ricardo (Principal)</li>
            <li>Renzo Rivera</li>
            <li>Muñoz Manrique Alejandra Melanie (Asistente)</li>
          </ul>
        </li>
        <li><strong>Introducción a la Computación:</strong> Quispe Zavala Rosmery Violeta (Asistente)</li>
      </ul>
    </section>

    <section id="companeros">
      <div class="dropdown">
        <button class="dropdown-btn" onclick="toggleDropdown()">Ver Compañeros de Carrera</button>
        <div class="dropdown-content" id="dropdown-list">
          <a href="https://deza-ccama.github.io/marilyn-shiomara-deza-ccama/" target="_blank">Marilyn Shiomara Deza Ccama</a>
          <a href="https://chaskacandia.github.io/chaskacandiaochoa.github.io/" target="_blank">Chaska Candia Ochoa</a>
          <a href="https://s-1018.github.io/Kelly-Coaguila-Quezada/" target="_blank">Kelly Coaguila Quezada</a>
          <a href="https://greciamunoz-sys.github.io/Grecia-Arianne-Consuelo-Munoz-Ventura/" target="_blank">Grecia Arianne Consuelo Muñoz Ventura</a>
          <a href="#">Mariana Montserrat Pacho Silva</a>
          <a href="#">Giovanni Andres Aguilar Marquez</a>
        </div>
      </div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>
        📧 <strong>Correo:</strong> <a href="mailto:Nayeli.Sucasaca@ucsp.edu.pe">Nayeli.Sucasaca@ucsp.edu.pe</a><br>
        📱 <strong>Teléfono:</strong> <a href="https://wa.me/51933131242" target="_blank">+51 933 131 242</a><br>
        🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/Nayeli-Katerine-Sucasaca-Lope-277079386/" target="_blank">Mi perfil profesional</a>
      </p>
    </section>
  </main>

  <footer>
    <p>© 2026 Nayeli Katerine Sucasaca Lope. Todos los derechos reservados.</p>
  </footer>

  <script>
    function toggleDropdown() {
      document.getElementById("dropdown-list").classList.toggle("show");
    }

    // Cerrar si se hace clic fuera
    window.onclick = function(event) {
      if (!event.target.matches('.dropdown-btn')) {
        var dropdowns = document.getElementsByClassName("dropdown-content");
        for (var i = 0; i < dropdowns.length; i++) {
          var openDropdown = dropdowns[i];
          if (openDropdown.classList.contains('show')) {
            openDropdown.classList.remove('show');
          }
        }
      }
    }
  </script>
</body>
</html>
