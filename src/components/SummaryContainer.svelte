<script>
  import DetailsSection from "./DetailsSection.svelte";
  import ResultSection from "./ResultSection.svelte";
</script>

<main>
  <ResultSection />
  <DetailsSection />
</main>

<style>
  main {
    background-color: #fff;
    min-height: 100dvh;
  }

  @media screen and (min-width: 32rem) {
    main {
      min-height: unset;
      border-radius: 2rem;
      overflow: hidden;
      min-width: 24rem;
    }
  }

  @media screen and (min-width: 50rem) {
    main {
      display: flex;
      width: 46rem;
    }
  }
</style>
