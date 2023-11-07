<script>
  import {cards} from '../data.js'
  export let title;
  export let description;
  export let image;
  export let url;
  export let alt;
</script>
{#each cards as {title, description, image, url, alt}}
<section class="bg-red-200 hover:bg-yellow-50 rounded-lg shadow-xl p-4 m-4 max-w-sm mx-auto">
<a href={url}>
  <article>
    <h2 class="text-xl font-bold mb-2">{title}</h2>
    <img src={image} alt={alt} class="w-full h-auto rounded-lg">
    <p class="text-gray-600 p-2">{description}</p>
  </article>
</a>
</section>
{/each}