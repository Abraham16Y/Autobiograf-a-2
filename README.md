# Autobiograf-a-2
<!DOCTYPE html><html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Autobiografía de <!-- Sustituye con tu nombre --> </title>
    <style>
      /* ======= VARIABLES DE DISEÑO ======= */
      :root {
        --color-primario: #004b8d;   /* Azul elegante */
        --color-secundario: #f2f5fa; /* Gris muy claro */
        --color-acento:   #f59e0b;  /* Dorado suave  */
        --fuente-titulos: "Georgia", serif;
        --fuente-texto:   "Helvetica Neue", Helvetica, Arial, sans-serif;
      }html { scroll-behavior: smooth; }

  body {
    margin: 0;
    font-family: var(--fuente-texto);
    background: var(--color-secundario);
    color: #333;
    line-height: 1.6;
  }

  /* ======= ENCABEZADO ======= */
  header {
    background: var(--color-primario);
    color: #fff;
    text-align: center;
    padding: 2.5rem 1rem;
  }
  header h1 {
    font-family: var(--fuente-titulos);
    font-size: 2.75rem;
    margin: 0;
  }
  header p { font-style: italic; margin-top: .5rem; }
  nav   { margin-top: 1rem; }
  nav a {
    color: #fff;
    margin: 0 .65rem;
    text-decoration: none;
    font-weight: bold;
  }
  nav a:hover { text-decoration: underline; }

  /* ======= SECCIONES ======= */
  section {
    max-width: 950px;
    margin: 3rem auto;
    background: #fff;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 4px 14px rgba(0,0,0,.06);
  }
  section:not(:last-of-type) { border-left: 8px solid var(--color-primario); }
  h2 {
    font-family: var(--fuente-titulos);
    color: var(--color-primario);
    margin-top: 0;
  }

  /* ======= TIMELINE ======= */
  .timeline { position: relative; margin-left: 1rem; padding-left: 1rem; }
  .timeline::before {
    content: ""; position: absolute; left: 0; top: 0; bottom: 0;
    width: 4px; background: var(--color-acento);
  }
  .timeline-entry {
    margin-bottom: 1.5rem; position: relative;
  }
  .timeline-entry::before {
    content: ""; position: absolute; left: -0.75rem; top: .35rem;
    width: 1rem; height: 1rem; background: var(--color-primario);
    border: 3px solid #fff; border-radius: 50%;
  }

  /* ======= GALERÍA ======= */
  .galeria {
    display: flex; flex-wrap: wrap; gap: 1rem; justify-content: center;
  }
  .galeria img {
    flex: 1 1 280px; /* crece, encoge, base */
    max-width: 100%; height: auto;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0,0,0,.15);
  }

  /* ======= PIE DE PÁGINA ======= */
  footer {
    text-align: center; padding: 1.5rem;
    background: var(--color-primario); color: #fff; margin-top: 4rem;
  }
  footer small { opacity: .8; }
</style>

  </head>
  <body>
    <!-- ================= ENCABEZADO ================= -->
    <header>
      <h1><!-- Sustituye con tu nombre completo --> · Mi Autobiografía</h1>
      <p>Una mirada íntima a mi historia, pasiones y sueños</p>
      <nav>
        <a href="#prologo">Prólogo</a>
        <a href="#infancia">Infancia</a>
        <a href="#adolescencia">Adolescencia</a>
        <a href="#intereses">Intereses</a>
        <a href="#galeria">Galería</a>
        <a href="#musica">Música</a>
        <a href="#logros">Logros</a>
        <a href="#futuro">Visión</a>
      </nav>
    </header><!-- ================= CONTENIDO ================= -->
<main>
  <!-- ======= PRÓLOGO ======= -->
  <section id="prologo">
    <h2>Prólogo</h2>
    <p>
      ¡Hola! Mi nombre es <!-- tu nombre --> y nací el <!-- fecha --> en
      <!-- ciudad, país -->. Actualmente tengo 17 años y estudio la preparatoria.
      Siempre he sido curioso, perfeccionista y guiado por la fe cristiana que
      practico junto a mi familia — mi padre es pastor —. Aquí comparto los
      momentos, sueños y aprendizajes que me forman.
    </p>
  </section>

  <!-- ======= INFANCIA ======= -->
  <section id="infancia">
    <h2>Infancia</h2>
    <p>
      Crecí rodeado de música en la iglesia: aprendí a cantar en el coro infantil y
      más tarde, de forma autodidacta, empecé a tocar la guitarra. Esos años moldearon
      mi amor por las artes y la disciplina.
    </p>
    <div class="timeline">
      <div class="timeline-entry"><strong>2008</strong> — Primer solo vocal frente a la congregación.</div>
      <div class="timeline-entry"><strong>2012</strong> — Aprendí mis primeros acordes de guitarra.</div>
    </div>
  </section>

  <!-- ======= ADOLESCENCIA ======= -->
  <section id="adolescencia">
    <h2>Adolescencia</h2>
    <p>
      Mi adolescencia es un balance entre mi naturaleza seria y mi deseo de conectar.
      Aunque la timidez y ciertas inseguridades me acompañan, trabajo cada día en
      proyectar elegancia, firmeza y serenidad.
    </p>
    <p>
      He compuesto canciones como <em>"Bajo el árbol"</em>, practico <em>indie&nbsp;folk</em> y
      participo en proyectos de animación 2D/3D a 24&nbsp;FPS. La creatividad es mi
      refugio y mi motor.
    </p>
  </section>

  <!-- ======= INTERESES Y PASIONES ======= -->
  <section id="intereses">
    <h2>Intereses y Pasiones</h2>
    <ul>
      <li>Aficionado al <strong>jazz</strong> y al <strong>folk</strong>; disfruto improvisar y descubrir nuevos sonidos.</li>
      <li>Hincha del <strong>FC Barcelona</strong>; el fútbol me inspira valores de trabajo en equipo.</li>
      <li>Tocar la <strong>guitarra</strong> y componer en BandLab.</li>
      <li>Lectura constante: novelas, ensayos y artículos académicos para nutrir mis textos.</li>
      <li>Admirador del actor <strong>Andrew Garfield</strong> por su versatilidad y carisma.</li>
      <li>Fotografía y edición en Lightroom; amo capturar <em>paisajes</em> que transmitan paz.</li>
      <li>Vestir de forma <strong>formal</strong>: suéteres, chalecos, corbatas y pantalones de vestir.</li>
      <li>Vida saludable: rutinas de ejercicio y alimentación equilibrada sin refrescos.</li>
    </ul>
  </section>

  <!-- ======= GALERÍA DE IMÁGENES ======= -->
  <section id="galeria">
    <h2>Galería</h2>
    <div class="galeria">
      <img src="https://photos.app.goo.gl/4oCZyMxJDLnaYnjD6" alt="Foto actual 1" loading="lazy">
      <img src="https://photos.app.goo.gl/QvvSXUT6dzQo6MKf6" alt="Foto actual 2" loading="lazy">
      <img src="https://photos.app.goo.gl/a6kTY8zjqKRBzKMi7" alt="Foto actual 3" loading="lazy">
    </div>
    <p style="text-align:center; margin-top:1rem; font-style:italic;">
      *Estas imágenes reflejan quién soy hoy: pasión, determinación y elegancia.*
    </p>
  </section>

  <!-- ======= MÚSICA ======= -->
  <section id="musica">
    <h2>Mi Banda Sonora</h2>
    <p>La música es la voz de mi alma. Dale <em>play</em> y acompáñame:</p>
    <div style="display:flex; justify-content:center;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/ZrPB_pvHXls" 
        title="Jazz favorito" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
  </section>

  <!-- ======= LOGROS ======= -->
  <section id="logros">
    <h2>Logros Destacados</h2>
    <ul>
      <li><strong>2024:</strong> Produje mi primera canción completa <em>"Ya no pasa más"</em> con BandLab.</li>
      <li><strong>2024:</strong> Lideré la adoración con <em>"Yeshúa"</em> en mi iglesia.</li>
      <li><strong>2025:</strong> Emprendí un proyecto de animación estilo anime (24&nbsp;FPS).</li>
      <li><strong>2025:</strong> Implementé una rutina fitness y plan de alimentación saludable.</li>
    </ul>
  </section>

  <!-- ======= VISIÓN A FUTURO ======= -->
  <section id="futuro">
    <h2>Visión a Futuro</h2>
    <p>
      Aspiro a estudiar <strong>Animación Multimedia</strong> y fusionar música, imagen y narrativa
      para inspirar a otros. Con disciplina, fe y pasión creativa, construiré un camino
      de impacto en la industria artística.
    </p>
  </section>
</main>

<!-- ================= PIE DE PÁGINA ================= -->
<footer>
  <small>&copy; <!-- año --> <!-- tu nombre --> · Todos los derechos reservados.</small>
</footer>

  </body>
</html>
