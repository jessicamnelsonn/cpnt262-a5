<script>
  import Card from '../Card.svelte';

  const cards = [
    {
      title: 'Card #1', 
      description: 'Text for #1',
      image: '/images/cocktail-number-1',
    },
    {
      title: 'Card #2',
      description: 'Text for #2',
      image: '/images/cocktail-number-2',
    },
    {
      title: 'Card #3',
      description: 'Text for #3',
      image: '/images/cocktail-number-3',
    },
  ];
</script>

<main>
  {#each cards as card (card.title)}
    <Card
      title={card.title}
      description={card.description}
      image={card.image}
    />
  {/each}
</main>

