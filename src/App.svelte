<main>
  <section class="faq-accordion">
    <header class="faq-header">
      <img class="star" src="./images/icon-star.svg" alt="" />
      <h1>FAQs</h1>
    </header>
    <details open>
      <summary class="faq-question">
        What is Frontend Mentor, and how will it help me?
        <span class="faq-button" aria-hidden="true"></span>
      </summary>
      <p class="faq-answer">
        Frontend Mentor offers realistic coding challenges to help developers
        improve their frontend coding skills with projects in HTML, CSS, and
        JavaScript. It's suitable for all levels and ideal for portfolio
        building.
      </p>
    </details>
    <hr />
    <details>
      <summary class="faq-question"
        >Is Frontend Mentor free?
        <span class="faq-button" aria-hidden="true"></span>
      </summary>
      <p class="faq-answer">
        Yes, Frontend Mentor offers both free and premium coding challenges,
        with the free option providing access to a range of projects suitable
        for all skill levels.
      </p>
    </details>
    <hr />
    <details>
      <summary class="faq-question"
        >Can I use Frontend Mentor projects in my portfolio?
        <span class="faq-button" aria-hidden="true"></span></summary
      >
      <p class="faq-answer">
        Yes, you can use projects completed on Frontend Mentor in your
        portfolio. It's an excellent way to showcase your skills to potential
        employers!
      </p>
    </details>
    <hr />
    <details>
      <summary class="faq-question"
        >How can I get help if I'm stuck on a challenge?
        <span class="faq-button" aria-hidden="true"></span>
      </summary>
      <p class="faq-answer">
        The best place to get help is inside Frontend Mentor's Discord
        community. There's a help channel where you can ask questions and seek
        support from other community members.
      </p>
    </details>
  </section>
</main>

<style>
  @font-face {
    font-family: "Work Sans";
    src: url("./fonts/WorkSans-VariableFont_wght.ttf")
      format("truetype-variations");
    font-weight: 400 700;
    font-style: normal;
  }

  :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  :global(body) {
    font-size: 16px;
    font-family: "Work Sans", sans-serif;
    --White: hsl(0, 100%, 100%);
    --Purple-100: hsl(275, 100%, 97%);
    --Purple-400: hsl(276, 89%, 52%);
    --Purple-600: hsl(292, 16%, 49%);
    --Purple-950: hsl(292, 42%, 14%);
  }

  main {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--Purple-100);
    min-height: 100dvh;
    background-image: url(./images/background-pattern-desktop.svg);
    background-repeat: no-repeat;
    background-size: 100%;
  }

  .faq-accordion {
    width: 34em;
    background: var(--White);
    padding: 2.5em 2.5em 1em 2.5em;
    border-radius: 0.8em;
  }

  .faq-header {
    display: flex;
    align-items: center;
    gap: 1em;
    margin-bottom: 0.75em;
  }

  .star {
    width: 2.2em;
    height: 2.2em;
  }

  .faq-header h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--Purple-950);
  }

  .faq-question {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 1rem;
    font-weight: 600;
    padding: 1em 0em;
    color: var(--Purple-950);
    outline: none;
    cursor: pointer;
  }

  .faq-answer {
    font-size: 0.875rem;
    color: var(--Purple-600);
    padding-bottom: 1.5em;
    line-height: 1.5;
  }

  hr {
    border: none;
    height: 0.5px;
    background: var(--Purple-100);
  }

  .faq-question:hover,
  .faq-question:focus {
    color: var(--Purple-400);
  }

  .faq-button {
    width: 1.75em;
    height: 1.75em;
    display: block;
    background-image: url("./images/icon-plus.svg");
    background-size: cover;
    background-repeat: no-repeat;
    flex-shrink: 0;
    margin-left: 1.25em;
  }

  details[open] .faq-button {
    background-image: url("./images/icon-minus.svg");
  }

  @media (max-width: 36.5625em) {
    main {
      background-image: url(./images/background-pattern-mobile.svg);
    }

    .faq-accordion {
      max-width: 87%;
      padding: 1.5em 1.5em 0.5em 1.5em;
      border-radius: 0.6em;
    }

    .faq-header {
      gap: 1.5em;
    }

    .star {
      width: 1.65em;
      height: 1.65em;
    }

    .faq-header h1 {
      font-size: 2rem;
    }
  }
</style>
