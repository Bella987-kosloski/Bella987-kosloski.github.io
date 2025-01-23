<script>
    import Personagem from '$lib/components/personagem.svelte';
    import { personagens } from '$lib/data.js';
</script>

<div class="row g-4">
    {#each personagens as personagem}
        <div class="col">
            <Personagem {...personagem} />
        </div>
    {/each}
</div>