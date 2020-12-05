<script lang="ts">
	import Display from './Components/Display.svelte';
import Loops from './Components/Loops.svelte';
import Toggle from './Components/Toggle.svelte';



	const pkg = {
		name: 'Svelte',
		version: 3,
		speed: 'blazing',
		website: 'https://svelte.dev'
	};
</script>

<main>
	<Display {...pkg} />
	<Toggle />
	<Loops />
</main>