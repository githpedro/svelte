<script>
    export let important;
    export let nombre = ""
    export let delFn;
    export let check;
    export let delM;
    export let checkTask;
    
    let aviso = "/img/aviso.png"

    $: if(check){
        checkTask(true)
    } else {
        checkTask(false)
    }
</script>

<main>
    <div class="juntos">
        {#if important}
            <img src={aviso} alt=""/>
        {/if}
        <input type="checkbox" name="check" id="check" bind:checked={check}>
        <h1 class={check?'tachado':'normal'}>{nombre}</h1>
    </div>
    <button id="x" on:click={delFn} on:click={delM}>X</button>
</main>

<style>
    main{
        display: flex;
        align-items: center;
        column-gap: 30rem;
        justify-content: center;
    }


    .tachado{
        text-decoration: underline;
        color:aqua
    }

    #x{
        height: 2rem;
        display: flex;
        align-items: center;
        background-color: red;
        color: white;
        
    }

    .juntos{
        column-gap: 2rem;
        display: flex;
    }

    h1{
        font-family: 'Courier New', Courier, monospace;
    }

    img{
        height: 4rem;
    }
</style>