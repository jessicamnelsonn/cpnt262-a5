<script>
  export let title;
  export let description;
  export let image;
  export let url;
</script>

<section>
<a href={url}>
  <article>
    <h2>{title}</h2>
    <img src={image} alt="">
    <p>{description}</p>
  </article>
</a>
</section>