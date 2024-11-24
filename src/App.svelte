<script>
  import Header from './lib/Header.svelte'
  import Footer from './lib/Footer.svelte'
  import InstagramLogo from './assets/instagramLogo.svg'
  import mailLogo from './assets/mailLogo.svg'
</script>

<!-- svelte-ignore a11y_invalid_attribute -->
<Header/>
<main>
  <section id="inicio">
    <h1 style="color: black; font-family: TAN Pearl;">BELLO DERM</h1>
    <h2 style="color: black; text-decoration: none; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif">
      PREOCUPADOS POR EL CUIDADO DEL CABELLO Y LA PIEL
    </h2>
  </section>

  <section id="quienes_somos">
    <h2>¿Quiénes somos?</h2>
    <p>Somos un equipo apasionado por el cuidado y la salud de la piel y el cabello, el cuál pretende ofrecer soluciones de alta calidad para mejorar la calidad de vida de nuestros clientes.</p>
    <p><strong>Ubicación:</strong> Granada</p>
  </section>

  <section id="valores">
    <h2>Valores</h2>
    <ul>
      <li><strong>Personalización:</strong> Creencia en el cuidado individualizado como la clave para la salud de la piel y el cabello.</li>
      <li><strong>Calidad:</strong> Búsqueda constante de los mejores productos e ingredientes.</li>
      <li><strong>Transparencia:</strong> Comunicación abierta y honesta con nuestros clientes sobre productos y procesos.</li>
      <li><strong>Innovación:</strong> Adaptación y evolución continua en respuesta a las necesidades de los consumidores.</li>
    </ul>
  </section>

  <section id="puntos_fuerte">
    <h2>Nuestros Puntos Fuertes</h2>
    <ul>
      <li><strong>Personalización:</strong> A partir de un análisis y diagnóstico realizado por expertos, se crean paquetes de productos recomendados para tratar necesidades específicas de la piel y cabello. Estos paquetes incluyen una guía detallada de uso para facilitar la rutina de cuidado.</li>
      <li><strong>Selección de Productos de Calidad:</strong> Se trabaja con laboratorios reconocidos que garantizan productos eficaces y seguros. No se desarrollan productos propios, sino que se seleccionan aquellos que cumplen con altos estándares de calidad.</li>
      <li><strong>Asesoría Integral:</strong> El cliente puede optar por una experiencia completa, desde el diagnóstico inicial hasta la adquisición de productos, o simplemente adquirir paquetes estándar diseñados para problemas comunes.</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Para más información, contáctanos a través de nuestro sitio web o redes sociales.</p>
    <p class="redes">
      <img src={mailLogo} class="logo" alt="InstagramLogo" style="height: 15px;" />
      <b>Correo:</b> bellodermcosmetologia@gmail.com
    </p>
    <p class="redes"><b>¡Síguenos en Instagram!</b></p>
    <div>
      <img src={InstagramLogo} class="logo" alt="InstagramLogo" style="height: 15px;" />
      <a href="https://www.instagram.com/bello_derm/?igsh=czVhbXNoOWgweWhl">@bello_derm</a>
    </div>
  </section>
</main>
<Footer/>

<style>
  main { background-color: #fcfbf7; padding: 20px; }
  
  section { margin-bottom: 50px; text-align: center; }
  
  h2 { font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; color: #333; text-decoration: underline; }
  
  p { 
    font-family: Arial, sans-serif; 
    color: #555; 
    max-width: 600px;
    line-height: 1.6;
    word-wrap: break-word;
    margin: 0 auto;
    text-align: justify;
    padding-bottom: 10px;
  }

  ul { font-family: Arial, sans-serif; color: #555; list-style-type: none; }
  
  li { 
    padding-bottom: 20px; 
    max-width: 600px;
    line-height: 1.6;
    word-wrap: break-word;
    margin: 0 auto;
    text-align: left;
  }

  .redes {
    text-align: center;
  }
</style>