<script setup>
</script>
<template>
  <main class="container">

    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand fs-4" href="/">
        <img src="/oursite-logo.png" width="40" height="40" role="icon" alt="logo">
        Oursite
      </a>

      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navoursite"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div
        id="navoursite"
        class="collapse navbar-collapse"
      >
        <ul class="navbar-nav">
          <li class="nav-item"><a href="/" class="nav-link link-light">Inicio</a></li>
          <li class="nav-item"><a href="#acerca" class="nav-link link-light">Acerca de nosotros</a></li>
          <li class="nav-item"><a href="#servicios" class="nav-link link-light">Servicios</a></li>
          <li class="nav-item"><a href="#procesos" class="nav-link link-light">Procesos de trabajo</a></li>
          <li class="nav-item"><a href="#contacto" class="nav-link link-light">Contacto</a></li>
        </ul>
      </div>
    </nav>

    <div class="row">

      <div class="col-sm-12 col-md-6 d-flex align-items-center">
        <div>
          <h1>
            Soluciones a medida, que se adaptan a la visión y los objetivos de tu negocio.
          </h1>
          <p >Transformando visiones en soluciones digitales.</p>
        </div>
      </div>
      <div class="col-sm-12 col-md-6">
        <img class="img-fluid" src="/flat-design-1.png" alt="Imagen de representacion" height="600">
      </div>
    </div>

    <div class="fs-5">

      <p class="mt-5">Somos un equipo experto en el desarrollo de sistemas
        web personalizados que potencian el crecimiento y la eficiencia de tu empresa.
        Nuestro enfoque se basa en la innovación, la calidad y la colaboración.
      </p>

      <h3 class="mt-5" id="acerca">Acerca de nosotros</h3>
      <p>
        Historia de la Empresa: "Con una sólida trayectoria en el mundo del desarrollo web,
        hemos ayudado a empresas de diversos sectores a alcanzar sus objetivos digitales. Nuestra
        pasión por la tecnología y el compromiso con la excelencia nos impulsan a ofrecer soluciones
        sobresalientes."
      </p>
      <p>
        Equipo: "Nuestro equipo está compuesto por ingenieros y diseñadores altamente capacitados,
        dedicados a crear sistemas web que superen las expectativas. Trabajamos en estrecha colaboración
        contigo para entender tus necesidades y convertirlas en realidades digitales.
      </p>

      <h3 class="mt-5" id="servicios">Servicios</h3>
      <p>
        Desarrollo de Aplicaciones Web: "Creamos aplicaciones web a medida que se adaptan perfectamente a
        tus procesos empresariales. Desde la planificación hasta la implementación, nos enfocamos en la
        usabilidad y el rendimiento."
      </p>
      <p>
        Diseño de Interfaz de Usuario (UI) y Experiencia de Usuario (UX): "Nuestros diseñadores transforman ideas
        en interfaces atractivas y funcionales. Priorizamos la experiencia del usuario para asegurar que cada
        interacción sea intuitiva y gratificante."
      </p>
      <p>
        Optimización y Mantenimiento: "No nos detenemos después del lanzamiento. Mantenemos tus sistemas web
        actualizados, seguros y en pleno rendimiento. Realizamos optimizaciones constantes para
        garantizar un funcionamiento sin problemas."
      </p>

      <h3 class="mt-5" id="procesos">Procesos de trabajo</h3>
      <p>
        Consulta y Planificación: "Comenzamos por comprender tus metas y desafíos. Luego, creamos un plan detallado que guiará todo el proceso de desarrollo."
      </p>
      <p>
        Diseño y Desarrollo: "Nuestro equipo diseña prototipos y desarrolla iterativamente tu sistema web, asegurando que cada funcionalidad esté alineada con tus objetivos."
      </p>
      <p>
        Pruebas y Optimización: "Realizamos pruebas exhaustivas para garantizar que tu sistema funcione de manera óptima en diversos escenarios. Realizamos ajustes y optimizaciones según sea necesario."
      </p>
      <p>
        Implementación y Soporte: "Una vez que todo esté listo, implementamos el sistema en tu entorno. Además, brindamos soporte continuo para resolver cualquier problema y asegurarnos de que estés satisfecho."
      </p>
    </div>

  </main>
  <!-- Footer -->
  <footer class="text-center text-lg-start bg-dark text-white mt-5" id="contacto">
    <!-- Section: Social media -->
    <section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom">
      <!-- Left -->
      <div class="me-5 d-none d-lg-block">
        <span>Conectate con nosotros o visita nustras redes sociales:</span>
      </div>
      <!-- Left -->

      <!-- Right -->
      <div>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-facebook-f"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-google"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold mb-4">
              <i class="fas fa-gem me-3"></i>oursite
            </h6>
            <p>
              Crear soluciones software a medida que potencien la transformación
              digital de empresas, entregando calidad y valor único,
              impulsando el éxito de nuestros clientes en un mundo digital en constante evolución.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">
              Products
            </h6>
            <p>
              <a href="#!" class="text-reset">Django</a>
            </p>
            <p>
              <a href="#!" class="text-reset">React</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Vue</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Laravel</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">
              Useful links
            </h6>
            <p>
              <a href="/" class="text-reset">Inicio</a>
            </p>
            <p>
              <a href="#acerca" class="text-reset">Acerca de nosotros</a>
            </p>
            <p>
              <a href="#servicios" class="text-reset">Servicios</a>
            </p>
            <p>
              <a href="#procesos" class="text-reset">Procesos de trabajo</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Contact</h6>
            <p><i class="fas fa-home me-3"></i> Salta, Gral Rauch 1786, ARG</p>
            <p>
              <i class="fas fa-envelope me-3"></i>
              ibarra.h.leonel@gmail.com
            </p>
            <p><i class="fas fa-phone me-3"></i> + 54 9387 4149 442</p>
            <p><i class="fas fa-user me-3"></i> Ibarra Hector Leonel</p>
          </div>
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05);">
      © 2023 Copyright:
      <a class="text-reset fw-bold" href="https://ihleonel.github.io/oursite/">Oursite.com</a>
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->
</template>
