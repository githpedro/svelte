<main>

    <div class="container-fluid row text-center p-5">

        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel" data-bs-pause="true">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1">
                <span></span>
              </button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2">
                <span></span>
              </button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3">
                <span></span>
              </button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="/img/video2.jpg" class="d-block w-100 carou" alt="...">
              </div>
              <div class="carousel-item">
                <img src="/img/video1.jpg" class="d-block w-100 carou" alt="...">
              </div>
              <div class="carousel-item">
                <img src="/img/video3.png" class="d-block w-100 carou" alt="...">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
        </div>


        <div class="container col-10 bg-1">
            <h2 class="p-5 t-stroke-shadow">Características</h2>
            <p> El Grado en Diseño de Videojuegos es una titulación oficial cuyo objetivo es formar a los 
                estudiantes para trabajar en la industria del desarrollo de videojuegos como profesional 
                especializado. Aprenderás a crear y programar para ser desarrollador de videojuegos en diferentes 
                plataformas y aplicaciones.
            </p>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">Plan de Estudios</h2>
            <p>El Grado en Diseño de Videojuegos es para ti si eres amante de los videojuegos, 
                creas historias, manejas las artes visuales y te vuelven loco/a las herramientas digitales y 
                multimedia.
            </p>
        </div>


        <div class="container col-10">
            <h2 class="p-5  t-stroke-shadow">Prácticas Profesionales</h2>
            <p>
                Las prácticas en empresas son un elemento clave en tu formación. Adquirir experiencia después 
                de lo aprendido en tu titulación, es la mejor forma de entrar en el mercado laboral. 
                Hay dos tipos de prácticas, las curriculares (incluidas en tu plan de estudios) y 
                extracurriculares (las que puedes hacer de forma voluntaria).
                Para realizar las prácticas curriculares en empresas, necesitarás tener el 50% de los créditos 
                aprobados y matricular la asignatura antes de comenzar tus prácticas. Estas prácticas llevan un 
                seguimiento por parte de la empresa y del profesor de prácticas, así como la realización de 
                informes intermedios y finales para su evaluación.
            </p>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow">Posibles trabajos</h2>
            <ul>
                <li>Game Designer</li>
                <li>Concept Artist</li>
                <li>Ilustrador 2D y 3D</li>
                <li>Rigger</li>
                <li>Diseñador de Serious Games</li>
                <li>Etc...</li>

            </ul>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow">Salidas profesionales</h2>
            <p>
                Los expertos en seguridad informática son muy valorados en las empresas y hay una gran demanda laboral a favor de estos perfiles. 
                Tras finalizar el Curso Ciberseguridad tendrás las competencias que necesitas para optar a puestos innovadores y de responsabilidad como analista 
                de ciberseguridad, auditor de ciberseguridad, gestor de seguridad informática, consultor de ciberseguridad, hacker ético o analista de Malware.
            </p>
        </div>

        <div class="container col-10 d-flex justify-content-center pt-5">
            <div class="accordion-item">
                <h1 class="accordion-header" id="headingTwo">
                  <button class="accordion-button collapsed acordeon" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                    More Info
                  </button>
                </h1>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <h4>Si quieres más información, solo deberás contactarnos al teléfono 
                            <a href="/">925284043</a> o bien al correo del centro <a href="/">45003875.ies@edu.jccm.es</a> 
                        </h4>
                    </div>
                </div>
              </div>
        </div>


    </div>

    <script src="/js/carrusel.js"></script>

</main>

<style lang="sass">
    ul
        text-align: left
        display: inline-block

    h2
        color: #009cde
        font-weight: bold
        text-decoration: underline

    h4
        font-style: italic
        background-color: black
        padding: 2rem
        margin: 10rem
        color: white
        border-radius: 2rem
        animation: message 3s infinite alternate-reverse
        
    .acordeon
        background-color: #F3F3F3
        padding: 1rem

    .acordeon:hover
        background-color: black
        color: white        
         

    a
        color: white

    .t-stroke-shadow 
        color: #009cde
        text-shadow: -3px 3px #ffffff, -3px -3px #ffffff, 3px -3px #ffffff, 3px 3px #f3f3f2, 6px 6px #6ac7c2


    .carou
        height: 25rem


    .carousel-indicators 
        [data-bs-target] 
            position: relative 
            width: 4rem 
            height: 1rem 
            border: none 
            border-radius: 10rem

            span 
                content: "" 
                position: absolute 
                top: 0 
                left: 0 
                width: 0 
                height: 100% 
                background: #009cde 
                border-radius: inherit 




@keyframes message
    from
        background-color: black
        
    to
        background-color: gray
        



</style>

