<script>
  import ResultsListItem from "./ResultsListItem.svelte";
</script>

<ul>
  <ResultsListItem
    className="reaction"
    category="Reaction"
    iconPath="icon-reaction.svg"
    score="80"
  />
</ul>

<style>
  ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
</style>
