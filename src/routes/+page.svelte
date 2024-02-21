<script>
</script>

{#await import('$lib/components/Player.svelte') then {default: Player}}
  <svelte:component this={Player} />
{/await}
