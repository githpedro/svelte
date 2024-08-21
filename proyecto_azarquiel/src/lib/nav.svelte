<script>
    
</script>

<main>
    <div class="container-fluid d-flex text-center">
        <div class="container col-lg-5 col-md-5 col-sm-5 img">
            <a href="/" onclick="location.reload()">
                <img src="/img/logoiesfseif.png" alt="">
            </a>
        </div>
        <div class="container col-lg-6 col-md-6 col-sm-4 align-items-center d-flex column-gap-4 linksmenu">
            <a href="/" class="esconder">INICIO</a>
            <a href="/" class="esconder">AL DIA</a>
            <a href="/" class="esconder">EL LORO</a>
            <a href="/" class="esconder">EL CENTRO</a>
            <a href="/" class="esconder">SECRETARIA</a>
            <a href="/" class="esconder">FAMILIAS</a>
            <a href="/" class="esconder">BOLSA</a>
            
            <i class="fa-solid fa-bars" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight"/>
            <div class="offcanvas offcanvas-end bg-dark text-white" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
                <div class="offcanvas-header  m-2">
                  <h5 id="offcanvasRightLabel">SEARCH</h5>
                  <button type="button" class="btn-close text-reset text-white bg-light" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <input name="searchword" id="mod-search-searchword" maxlength="200" class="inputbox search-query text-white bg-dark search" type="text" placeholder="Search ...">
                <div class="offcanvas-body">
                    
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> INICIO</a></li>
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> AL DIA</a></li>
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> EL LORO</a></li>
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> EL CENTRO</a></li>
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> SECRETARIA</a></li>
                    <li class="current active float-left d-flex p-2" ><a href="/" class="text-white">> FAMILIAS</a></li>
                    <li class="current active float-left d-flex p-2"><a href="/" class="text-white">> BOLSA</a></li>
                    
                </div>
            </div>
        </div>
    </div>
            
            
 
</main>


<style lang="sass">
    main
        justify-content: center
        align-items: center
        display: flex
        padding: 1rem
        position: sticky
        top: 0
        z-index: 111
        background-color: white
        width: 100%
        box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.05) 0px 4px 6px -2px

        img
            height: 3rem

        .linksmenu
            font-size: 0.71rem
            display: flex

            

            a
                text-decoration: none
                color: gray

                
            i
                font-size: 1rem
                cursor: pointer

        .offcanvas
            width: 20rem
            color: white
            z-index: 10000000000

            .offcanvas-body
                font-size: 1rem
                color: white
                margin-top: 5rem

            .search
                width: 15rem
                font-size: 1rem
                margin: auto
                border: 1px solid white
                padding: 0.5rem





                

@media screen and ( max-width: 1100px )
    .esconder 
        display: none

    



        
</style>

