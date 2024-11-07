<script lang="ts">
	import formValidator from "$lib/formValidator";
	import { Card, Input } from "flowbite-svelte";
    

	let formValues = $state({ name: "", age: 0 });
    let errors = $derived(formValidator(formValues));
</script>

<p>Testing ko lang</p>