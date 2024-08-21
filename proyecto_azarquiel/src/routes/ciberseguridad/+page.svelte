<main>
    <div class="container-fluid row text-center p-5">
        <div id="carouselExampleIndicators" class="carousel slide" data-interval="4000" data-bs-ride="carousel" data-bs-pause="false">
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
                <img src="/img/ciber2.jpg" class="d-block w-100 carou" alt="...">
              </div>
              <div class="carousel-item">
                <img src="/img/ciber1.jpg" class="d-block w-100 carou" alt="...">
              </div>
              <div class="carousel-item">
                <img src="/img/ciber3.png" class="d-block w-100 carou" alt="...">
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
        
        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">Presentacion</h2>
            <p> La dependencia, cada vez mayor, por parte de las organizaciones de los sistemas informáticos, 
                ha creado la necesidad de contar con un equipo especializado que los proteja de ataques informáticos. 
                Con el Curso Ciberseguridad formarás parte de los profesionales en seguridad informática que garantizan 
                la protección del activo más importante de las empresas: la información. Consigue un perfil informático versátil y actualizado, fórmate.
            </p>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">Para qué te prepara</h2>
            <p>El Curso Ciberseguridad te formará en las principales técnicas, herramientas y legislación entorno a la seguridad informática. 
                Con él podrás realizar auditorías de seguridad informática y aplicar el hacking ético o la ingeniería inversa para hacer frente al malware. 
                Obtendrás las competencias necesarias para afrontar ataques informáticos y tener una visión global de la ciberseguridad en redes de área local 
                y entornos móviles.
            </p>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">Objetivos</h2>
            <ul>
                <li>Obtener una visión global de la ciberseguridad y la ciberinteligencia</li>
                <li>Asimilar los conocimientos y técnicas de ingeniería inversa  y análisis de Malware</li>
                <li>Afianzar los conocimientos necesarios para conocer los fallos de ciberseguridad</li>
                <li>Conocer el hacking ético y aplicarlo en ataques a sistemas y redes</li>
                <li>Aplicar la ciberseguridad en entornos móviles y sistemas de control industria</li>
            </ul>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">A quién va dirigido</h2>
            <p>
                El Curso Ciberseguridad está dirigido a estudiantes, graduados y profesionales de la informática y las telecomunicaciones que quieran 
                diferenciarse a través de la profundización del estudio de la seguridad informática, hacking ético, auditoría de seguridad, ingeniería inversa, etc. 
                Igualmente se dirige a aquellas personas que quieran orientar su carrera profesional hacia la ciberseguridad.  
            </p>
        </div>

        <div class="container col-10">
            <h2 class="p-5 t-stroke-shadow ">Salidas profesionales</h2>
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

        <script src="/js/carrusel.js"></script>  
    </div>

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

        a
            color: white

        @keyframes message
            from
                background-color: black
                    
            to
                background-color: gray

    .t-stroke-shadow 
        color: #009cde
        text-shadow: -3px 3px #ffffff, -3px -3px #ffffff, 3px -3px #ffffff, 3px 3px #f3f3f2, 6px 6px #6ac7c2

    
    .acordeon
        background-color: #F3F3F3
        padding: 1rem

    .acordeon:hover
        background-color: black
        color: white    


    .carou
        height: 30rem


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

</style>

