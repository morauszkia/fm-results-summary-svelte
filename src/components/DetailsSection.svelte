<script>
  import ResultsList from "./ResultsList.svelte";

  let { results } = $props();
</script>

<section>
  <h2>Summary</h2>
  <ResultsList {results} />
  <button>Continue</button>
</section>

<style>
  section {
    padding: 1.875rem;
    padding-top: 1.5rem;
    background-color: #fff;

    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 1.5rem;
    flex: 1 0 50%;
  }

  h2 {
    font-size: var(--fs-md);
    color: #303b59;
  }

  button {
    --start: #303b59;
    --end: #303b59;
    background: linear-gradient(var(--start), var(--end));
    color: #fff;
    font-size: 1.125rem;
    font-weight: 700;
    padding: 1rem 0;
    border-radius: 100px;
    cursor: pointer;
    border: none;
    transition: all 0.3s;
  }

  button:hover,
  button:focus {
    --start: #6943ff;
    --end: #2f2ce9;
    outline: 0;
  }

  button:active {
    transform: scale(0.95);
  }

  @media screen and (min-width: 50rem) {
    section {
      padding: 2.375rem 2.875rem 2.875rem 2.875rem;
    }
  }
</style>
