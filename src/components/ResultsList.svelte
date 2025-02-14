<script>
  import ResultsListItem from "./ResultsListItem.svelte";

  let { results } = $props();
</script>

<ul>
  {#each results as result}
    <ResultsListItem
      className={result.category.toLowerCase()}
      category={result.category}
      iconPath={result.icon}
      score={result.score}
    />
  {/each}
</ul>

<style>
  ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
</style>
