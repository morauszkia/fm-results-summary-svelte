<section>
  <h1>Your Result</h1>
  <p class="average--text">
    <span class="average--value">76</span> <span>of 100</span>
  </p>
  <div>
    <p class="evaluation">Great</p>
    <p class="comparison">
      You scored higher than 65% of the people who have taken these tests.
    </p>
  </div>
</section>

<style>
  section {
    background: linear-gradient(to bottom, #6943ff, #2f2ce9);

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
    padding: 1.5rem;
    padding-bottom: 2.5rem;
    border-bottom-left-radius: 2rem;
    border-bottom-right-radius: 2rem;
    text-align: center;
    flex: 1 0 50%;
  }
  h1,
  p {
    color: #cac9ff;
    font-weight: 700;
  }
  h1 {
    font-size: var(--fs-md);
  }
  .average--text {
    height: 8.75rem;
    width: 8.75rem;
    border-radius: 50%;
    background: linear-gradient(to bottom, #4d21c999, #2521c900);

    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }

  .average--value {
    color: #fff;
    font-size: var(--fs-xl);
    font-weight: 800;
    display: block;
  }

  .evaluation {
    font-size: var(--fs-lg);
    color: #fff;
    margin-bottom: 0.5rem;
  }

  .comparison {
    font-weight: 500;
    max-width: 16rem;
    line-height: 1.31;
    font-size: var(--fs-sm);
  }

  @media screen and (min-width: 50rem) {
    section {
      border-top-right-radius: 2rem;
      padding: 2.375rem 2.875rem 2.875rem 2.875rem;
    }

    .average--text {
      width: 12.5rem;
      height: 12.5rem;
    }

    .evaluation {
      margin-bottom: 0.875rem;
    }
  }
</style>
