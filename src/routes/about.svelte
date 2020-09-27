<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<style lang="scss">
	h1 {
		color: blue;
	}
</style>

<TextField validate={() => {}} validity={writable({})} />

	<CheckIcon />


<script>
	import { writable } from 'svelte/store'
	import { TextField } from '@beyonk/fields'
	import { CheckIcon } from 'svelte-feather-icons'
</script>