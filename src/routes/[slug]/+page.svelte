<script>
	import { page } from '$app/stores'
	import Normalizer from "../Normalizer.svelte";
	
	export let data;
	export let value = $page.params.slug;
</script>
<title># to t.me/wa.me</title>

<Normalizer data={data} value={value}>

</Normalizer>