<script></script>

<style lang="scss">
$fontSizes: (
  "large": 24px,
  "medium": 20px,
);

main {
  text-align: center;
  padding: 1em;
  max-width: 240px;
  margin: 0 auto;
  .article {
    font-size: map-get($fontSizes, "large");
  }
}

@media (min-width: 640px) {
  main {
    max-width: none;
  }
}
</style>

<main>
  <article class="article">
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
  </article>
</main>
