<script>

</script>

<main>
    <div class="card-group container-fluid row">
        <div class="container card pt-4 col-lg-6 col-md-12 col-sm-12 uno">
          <img src="/img/fondociber.gif" class="card-img-top pt-4" alt="" />
          <div class="card-body">
            <h5 class="card-title"><li>Curso de Ciberseguridad</li></h5>
            <p class="card-text">
              El Ciclo de Ciberseguridad se divide en dos semestres, el primero empieza en septiembre y el segundo en febrero.
              Conviértete en un experto en Ciberseguridad, el perfil más demandado por las empresas.
            </p>
            <p class="card-text" >
              <a  href="/ciberseguridad" class="text-white botoncurso" >¡Ir al curso!</a>
            </p>
          </div>
        </div>
        <div class="container card pt-4 col-lg-6 col-md-12 col-sm-12">
          <img src="/img/fondovideo.gif" class="card-img-top pt-4" alt="" />
          <div class="card-body">
            <h5 class="card-title"><li>Curso de Videojuegos</li></h5>
            <p class="card-text">¿Te gustaría trabajar dando forma a las ideas, propias o ajenas, relacionadas con el mundo gamer? ¡Entonces este curso está hecho para ti!
            </p>
            <p class="card-text">
                <a href="/videojuegos" class="text-white botoncurso">¡Ir al curso!</a>
            </p>
          </div>
        </div>

    </div>


</main>

<style lang="sass">
.uno
  margin-right: 10rem

.card-group
    padding: 2rem
    

img
    width: 20rem
    height: 15rem
    margin: auto
    animation: img 6s  
    animation-fill-mode: forwards


.card
    border: 3px solid white
    animation: cards 6s
    z-index: 0



.card:hover
    animation: bord 3s infinite alternate

    @keyframes bord 
      from
        border: 10px solid #009cde
      to
        border: 10px solid white
        border-radius: 5rem
    

    .card-title
      font-size: 2rem
      font-style: italic

    img
      filter: saturate(500%)
      

.card-title
    padding: 1rem
    font-style: bold

.botoncurso
    display: flex
    align-items: center
    justify-content: center
    text-decoration: none
    padding: 1rem
    background-color: gray
    border-radius: 1rem
    position: relative
    bottom: 0
    left: 0

.botoncurso:hover
    background-color: #009cde



@keyframes cards 
  from
    opacity: 0
  to
    opacity: 1

@keyframes img 
  from
    border-radius: 0

  to
    border-radius: 5rem


</style>