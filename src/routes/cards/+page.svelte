<script>
  import Card from '../../lib/components/Card.svelte';  // Import the Card component
  import { cards } from '../../lib/data.js';
</script>

{#each cards as card}
  <Card {...card} />
{/each}

