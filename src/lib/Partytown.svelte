<script>
	export let script = '';

	$: partytownScript = `<sc` + `ript type="script/partytown">${script}</scr` + `ipt>`;
</script>

{@html partytownScript}
