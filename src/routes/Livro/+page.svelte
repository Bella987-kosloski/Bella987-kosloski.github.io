<script>
    import {livros} from '$lib/livros.js';
    import Livro from '$lib/componentes/Livro.svelte';

</script>

<div class="row g-4">
    {#each livros as livro} 
        <div class="col">
            <Livro {...livro} /> 
        </div>
    {/each}
</div>
