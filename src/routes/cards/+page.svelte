<script>
  import Card from '../../lib/components/Card.svelte';  // Import the Card component
  import { cards } from '../../lib/data.js';
</script>

<h1 class="text-4xl text-center p-4 font-mono">Our Featured Cocktails</h1>

{#each cards as card}
  <Card {...card} />
{/each}

