<main>
  <section class="faq-accordion">
    <header class="faq-header">
      <img class="star" src="./public/images/icon-star.svg" alt="" />
      <h1>FAQs</h1>
    </header>
    <details open>
      <summary class="faq-question">
        What is Frontend Mentor, and how will it help me?
        <span class="faq-button" aria-hidden="true"
          ><img src="./public/images/icon-plus.svg" alt="" /></span
        >
      </summary>
      <p class="faq-answer">
        Frontend Mentor offers realistic coding challenges to help developers
        improve their frontend coding skills with projects in HTML, CSS, and
        JavaScript. It's suitable for all levels and ideal for portfolio
        building.
      </p>
    </details>
    <details>
      <summary class="faq-question"
        >Is Frontend Mentor free?
        <span class="faq-button" aria-hidden="true"
          ><img src="./public/images/icon-plus.svg" alt="" /></span
        >
      </summary>
      <p class="faq-answer">
        Yes, Frontend Mentor offers both free and premium coding challenges,
        with the free option providing access to a range of projects suitable
        for all skill levels.
      </p>
    </details>
    <details>
      <summary class="faq-question"
        >Can I use Frontend Mentor projects in my portfolio?
        <span class="faq-button" aria-hidden="true"
          ><img src="./public/images/icon-plus.svg" alt="" /></span
        ></summary
      >
      <p class="faq-answer">
        Yes, you can use projects completed on Frontend Mentor in your
        portfolio. It's an excellent way to showcase your skills to potential
        employers!
      </p>
    </details>
    <details>
      <summary class="faq-question"
        >How can I get help if I'm stuck on a challenge?
        <span class="faq-button" aria-hidden="true"
          ><img src="./public/images/icon-plus.svg" alt="" /></span
        >
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
    font-family: 'Work Sans';
    src: url('/fonts/WorkSans-VariableFont_wght.ttf') format('truetype-variations');    
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
    font-family: 'Work Sans', sans-serif;
    --White: hsl(0, 100%, 100%);
    --Purple-100: hsl(275, 100%, 97%);
    --Purple-600: hsl(292, 16%, 49%);
    --Purple-950: hsl(292, 42%, 14%);
  }

  main {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--Purple-100);
    min-height: 100dvh;
    background-image: url(./public/images/background-pattern-desktop.svg);
    background-repeat: no-repeat;
    background-size: 100%;
  }

  .faq-accordion {
    width: 35em;
    background: var(--White);
    padding: 2em;
    border-radius: 0.8em;

  }

  .faq-header {
    display: flex;
    align-items: center;
    gap: 1em;
  }

  .star {
    width: 28px;
    height: 28px;
  }

  .faq-header h1 {
    font-size: 2.5rem;
    font-weight: 700;
  }

  .faq-question {
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 1rem;
    font-weight: 600;
    border-bottom: 1px solid grey;
  }
</style>
