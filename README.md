<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="keyword" content="Nayeli Katerine Sucasaca Lope" />
  <title>Nayeli Katerine Sucasaca Lope</title>
<style>
    body {
      /* Fondo general de la página en blanco */
      background-color: #ffffff; 
      color: #4a148c; /* Texto principal en morado oscuro */
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      /* Encabezado en morado vibrante */
      background-color: #7b1fa2; 
      color: white;
      padding: 20px;
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
      /* Las tarjetas ahora tienen un fondo muy suave para resaltar sobre el blanco */
      background-color: #f3e5f5; 
      border-left: 5px solid #9c27b0; /* Borde lateral morado */
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #4a148c; /* Títulos en morado oscuro */
      margin-bottom: 10px;
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
    }

    ul {
      list-style: none;
      padding-left: 20px;
    }

    /* Dropdown - Botones en morado */
    .dropdown-btn {
      background-color: #9c27b0;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .dropdown-btn:hover {
      background-color: #7b1fa2;
    }

    .dropdown-content {
      display: none;
      margin-top: 10px;
      background-color: #f3e5f5;
      border-radius: 6px;
      padding: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .show {
      display: block;
    }

    footer {
      background-color: #7b1fa2;
      color: white;
      text-align: center;
      padding: 15px 0;
      width: 100%;
      box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
    }
</style>
<body>
  <header>
    <h1>Perfil de Nayeli Katerine Sucasaca Lope</h1>
  </header>
  
<section>
  <h2>Biografía</h2>
  <div style="text-align: center; margin-bottom: 15px;">
    <img src="foto.jpg" alt="Nayeli Sucasaca" style="width: 150px; border-radius: 50%;">
  </div>
  <main>
    
      <p>
        Hola, mi nombre es <strong>Nayeli Katerine Sucasaca Lope</strong>, estudiante de Contabilidad en la 
        <a href="https://ucsp.edu.pe/" target="_blank">Universidad Católica San Pablo (UCSP)</a> 
        de Arequipa, Perú. con 20 años de edad. Me defino como una persona analítica y detallista, apasionada por las finanzas y la gestión empresarial como motores de crecimiento sólido. Mi objetivo es trascender los libros de texto para aplicar normativas y conocimientos técnicos en entornos reales, buscando siempre generar orden e impacto positivo tanto en equipos creativos como en la estrategia corporativa. 
        <a href="https://ucsp.edu.pe/facultad-de-ciencias-economicas-y-empresariales/carrera-de-contabilidad/" target="_blank">Contabilidad</a>.
      </p>
    </section> 

    <section id="cursos">
      <h2>Cursos</h2>
      <ul>
        <li>Contabilidad III</li>
        <li>Legislación laboral</li>
        <li>Legislación y auditoria tributaria</li>
        <li>Cálculo en una variable</li>
        <li>Estadística y probabilidades</li>
        <li>Introducción de computación</li>
      </ul>
    </section>

    <section id="docentes">
     <section>
  <h2>Perfiles de mis docentes</h2>
  <ul>
    <li><strong>Contabilidad III:</strong> 
      <a href="mailto:ggarciaj@ucsp.edu.pe">García Jarufe Giovanna María</a>
    </li>

    <li><strong>Legislación Laboral:</strong> 
      <ul>
        <li><a href="#">Abarca Rubianes Carlos Rodrigo</a> (Adjunto)</li>
        <li><a href="mailto:ggarciaj@ucsp.edu.pe">García Jarufe Giovanna María</a> (Principal)</li>
      </ul>
    </li>

    <li><strong>Legislación y Auditoría Tributaria:</strong> 
      <a href="#">Amat y León Arispe Juan Sebastian</a>
    </li>

    <li><strong>Cálculo en una Variable:</strong> 
      <a href="#">Rendón García Fiorella María</a>
    </li>

    <li><strong>Estadística y Probabilidades:</strong> 
      <ul>
        <li><a href="#">Enriquez Cáceres Ricardo</a> (Principal)</li>
        <li><a href="#">Renzo Rivera</a></li>
        <li><a href="#">Muñoz Manrique Alejandra Melanie</a> (Asistente)</li>
      </ul>
    </li>

    <li><strong>Introducción a la Computación:</strong> 
      <a href="#">Quispe Zavala Rosmery Violeta</a> (Asistente)
    </li>
  </ul>
</section>

<section>
  <div class="dropdown">
    <button class="dropdown-btn" onclick="toggleDropdown()">Ver Compañeros</button>
    <div class="dropdown-content" id="dropdown-list">
      <a href="https://deza-ccama.github.io/marilyn-shiomara-deza-ccama/" target="_blank">Marilyn Shiomara Deza Ccama</a>
      <a href="https://chaskacandia.github.io/chaskacandiaochoa.github.io/" target="_blank">Chaska Candia Ochoa</a>
      <a href="https://s-1018.github.io/Kelly-Coaguila-Quezada/" target="_blank">Kelly Coaguila Quezada</a>
      <a href="#">Mariana Montserrat Pacho Silva</a>
      <a href="#">Giovanni Andres Aguilar Marquez</a>
      <a href="https://greciamunoz-sys.github.io/Grecia-Arianne-Consuelo-Munoz-Ventura/" target="_blank">Grecia Arianne Consuelo Muñoz Ventura</a>
    </div>
  </div>
</section>

    <section id="contacto">
  <h2>Contacto</h2>
  <p>
    📧 <strong>Correo electrónico:</strong> 
    <a href="mailto:Nayeli.Sucasaca@ucsp.edu.pe">Nayeli.Sucasaca@ucsp.edu.pe</a><br>

    📱 <strong>Teléfono:</strong> 
    <a href="https://wa.me/51933131242" target="_blank">+51 933 131 242</a><br>

    🔗 <strong>LinkedIn:</strong> 
    <a href="https://www.linkedin.com/in/Nayeli-Katerine-Sucasaca-Lope-277079386/" target="_blank">Mi perfil de LinkedIn</a>
  </p>
</section>

  <footer>
    <p>© 2026 Nayeli Katerine Sucasaca Lope. Todos los derechos reservados.</p>
  </footer>

  <script>
    function toggleDropdown() {
      document.getElementById("dropdown-list").classList.toggle("show");
    }
  </script>
</body>
</html>
