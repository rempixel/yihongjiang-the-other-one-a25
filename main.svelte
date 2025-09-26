<script>
import Canvas from './canvas.svelte';

const background = '#fff'

</script>

<main>
    <Canvas {background}/>
</main>

<style>
    main {
        max-width: 300px;
        display: flex;
        flex-direction: column;
        gap: 0.5rem 0;
	}
</style>
