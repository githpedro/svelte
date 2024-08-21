<script>
    import Item from "../lib/item.svelte";
    import { browser } from "$app/environment";
    


    let tareas = [];
    let checkImportant = false;


    const recheckTask = (check, n) => {
        tareas[n].completado = check;
        tareas = tareas;
        saveList();
    };



    
    if(browser){
        tareas = JSON.parse(localStorage.getItem("lista")) || [];
    }

    const saveList = () =>{
        if(browser){
            localStorage.setItem("lista", JSON.stringify(tareas));
        }
    }

    let textoTarea = "";

    class Task{
        constructor(nombre, completado = false, important = false){
            this.completado = completado;
            this.nombre = nombre;
            this.important = important
        }
    }


    const addTask = () =>{
        // if(input.valueOf != null){

            let nuevaTarea = new Task(textoTarea, false, checkImportant);
            tareas.push(nuevaTarea)
            textoTarea = ""
            tareas=tareas
            saveList()
        
    }

    const removeTask = (n) =>{
        tareas.splice(n,1)
        tareas=tareas
        saveList()
    }

    const mensaje = () =>{
        alert("Tarea Eliminada")
    }


</script>

<main>
    <h1> Lista de tareas</h1>

    <input type="text" name="" id="añadir" bind:value={textoTarea}>
    <button on:click={addTask}>Añadir tarea</button>
    <div class="imp">
        <input type="checkbox" name="checkIm" id="checkIm" bind:checked={checkImportant}/>
        <label for="">Importante</label>
    </div>

    {#each tareas as tarea,i}
        <Item 
            nombre = {tarea.nombre} 
            checkTask={(check) => recheckTask(check, i)}
            delFn={() => removeTask(i)} 
            delM={() => mensaje()}
            important={tarea.important}
        />
    {/each}
</main>

<style>
    :global(body){
        background-color: rgb(0, 94, 97);
        text-align: center;
        color: white;
    }

    button{
        background-color: bisque;
        border: 2px solid white;
        padding: 1rem;
    }

    button:hover{
        background-color: aqua;
    }

    #añadir{
        height: 2rem;
    }

    .imp{
        padding: 1rem;
    }

    h1{
        color: wheat;
        text-decoration: underline;
    }
</style>