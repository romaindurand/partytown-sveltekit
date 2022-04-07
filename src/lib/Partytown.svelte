<script>
	export let script = '';

	$: partytownScript = `<sc` + `ript type="text/partytown">${script}</scr` + `ipt>`;
</script>

{@html partytownScript}
