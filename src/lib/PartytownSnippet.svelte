<script>
	import { partytownSnippet } from '@builder.io/partytown/integration';
	const partytown = partytownSnippet();
</script>

<svelte:head>
	{@html `<scr` + `ipt>${partytown}</script>`}
</svelte:head>
