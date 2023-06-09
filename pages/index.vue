<template>
  <article>
    <div class="gr-hero">
      <img src="/images/hero.jpg" alt="Hero" class="gr-hero__image" aria-hidden="true" />
      <div class="gr-hero__content">
        <stack-l space="var(--s1)" class="gr-hero__info">
          <h1 class="gr-hero__title">Supporting Gender Equality Outcomes in Development Research</h1>
          <p class="gr-hero__tagline">Reflections on a Multi-year Collaboration between Gender at Work, IDRC and its Partners</p>
          <p class="gr-hero__date">May 2023</p>
        </stack-l>
        <base-button class="gr-hero__button" color="white">Download Publication</base-button>
        <ul class="gr-hero__editors">
          <li class="gr-hero__editors-title">Edited by:</li>
          <li>David Kelleher</li>
          <li>Carol Miller</li>
          <li>Rex Fyles</li>
        </ul>
      </div>
    </div>
    <center-l size="wide" class="gr-logos-container">
      <div class="gr-logos">
        <a href="https://idrc-crdi.ca/" target="_blank" class="gr-logo">
          <img src="/images/idrc-logo.png" alt="IDRC CRDI" />
        </a>
        <a href="https://genderatwork.org/" target="_blank" class="gr-logo">
          <img src="/images/gender-at-work-logo.png" alt="Gender at work" />
        </a>
      </div>
    </center-l>
    <center-l class="gr-content" size="wide">
      <div class="prose">
        <h2 class="gr-title">Executive Summary</h2>
        <p>The degree to which gender is studied or ignored in research can powerfully affect both research results and the communities those outcomes were intended to benefit. Yet, science and technology have historically and consistently ignored gender gaps. Critiques of systematic biases in research have made visible a multitude of biases and assumptions underpinning research and contributing to gender and diversity related data gaps. These biases are consistent with patriarchal and other social and power relations in societies, which in many countries in the Global South may be endogenous and/or the result of contact with colonial systems. Until recently such norms, and the barriers they create, have been invisible in research.</p>
        <p>This monograph makes the case for a process-driven methodology that supports research institutions, and other development institutions, to fill the implementation gaps that are often found between formal gender policies and strategies, and the hoped-for gender equality outcomes. It draws on the experience of five International Development Research Centre research programs Gender at Work worked with between 2016 and 2022.</p>
        <p>During this period, Gender at Work ‘deployed’ twenty individuals in different team configurations to work with dozens of IDRC staff members, individual researchers and research institutions working on scores of projects related to fields as diverse as digital technologies, food and health, climate change and education. Operating in multiple languages and using a range of engagement methods, the entry point, duration, reach and precise methods G@W team members used in each intervention varied widely. After six years, scores of people and dozens of organizations in more than 15 countries are now doing research differently. Attitudes have changed, new methods have been adopted, new ways of working with grantees have emerged, and new knowledge has been created.</p>
        <p>G@W’s approaches were originally a marriage of feminist theory and organizational learning. The emphasis of this approach is not to specify what is required and then monitor for gender compliance but rather focusses learning, relationships and action. In our work with IDRC and its partners, this learning led to a wide range of gender responsive outcomes, including shifts in methodology of a single project, changes in a research team’s overall approach to research, shifts in a research groups norms, practices and policies, shifts in research influence and shifts in grantmaking procedures, staff skills changes, organizational norms and processes within IDRC itself.</p>
        <p>This document is organized into five chapters. In the first chapter we review existing studies on the problem of gender equality and inclusion in development research: overviewing strategies that have been used in trying to bring gender equality considerations to research institutions globally and to the research itself; and describing the G@W approach and framework that guided our work with IDRC programs. The next three chapters describe the process and achievements in the various projects – how we started, the change process and outcomes. Finally, the conclusion pulls together the main learnings from these six years of work.</p>
        <p>At the beginning we posed the question: What does it take to improve gender equality outcomes in development research? This reflection Gender at Work has engaged in with IDRC and its partners over the past six years allowed us to identify six ideas that best respond to this framing question:</p>
        <p>Change happens as a result of a judicious mixture of pressure and support.</p>
        <p>Learning and change happen within reflective spaces that are characterized by trust, openness, creativity and personal exploration.</p>
        <p>Learners will be motivated to solve problems which they have the power to define in terms that matter to them.</p>
        <p>Providing conceptual material regarding gender and inclusion is only valuable when it is offered to shed light on a problem the research team is confronting.</p>
        <p>Transformative change happens over time.</p>
        <p>Change requires some sort of ‘upset’, often called disconfirmation.</p>
      </div>
    </center-l>
    <div class="footer">  
      <center-l class="copy">
        <p>Designed by <a href="https://www.ccmdesign.ca/" target="_blank">CCM Design</a> - 2023</p>
      </center-l>
    </div>
  </article>
</template>

<script>
</script>

<style scoped lang="scss">
  .gr-hero {
    display: flex;
    flex-direction: row;
    background-color: var(--base-color);
    color: var(--white-color);
    @media (max-width: 52em) {
      flex-direction: column;
    }
    @media (min-width: 74em) {
      justify-content: flex-end;
      height: 640px;
    }
  }

    .gr-hero__image {
      height: 75vh;
      @media (max-width: 52em) {
        height: auto;
        width: 100%;
      }
      @media (min-width: 74em) {
        width: 640px;
        height: 640px;
        position: fixed;
        top: 0;
        left: 0;
      }
    }

    .gr-hero__content {
      padding: var(--s3) var(--s2);
      display: flex;
      flex-flow: column nowrap;
      align-items: flex-start;
      justify-content: space-between;
      @media (max-width: 36em) {
        padding: var(--s2) var(--s1);
      }
      @media (min-width: 74em) {
        width: calc(100% - 640px);
      }
    }

    .gr-hero__info {
      @media (max-width: 36em) {
        margin-bottom: var(--s2);
      }
    }

    h1.gr-hero__title {
      color: var(--white-color);
      font-size: 1.5em;
      @media (max-width: 36em) {
        font-size: 1.125em;
      }
    }

    .gr-hero__tagline {
      font-size: 1.125em;
      @media (max-width: 36em) {
        font-size: 0.875em;
      }
    }

    .gr-hero__date {
      font-weight: 700;
      text-transform: uppercase;
      font-size: 0.75em;
      @media (max-width: 36em) {
        display: none;
      }
    }

    .gr-hero__button {
      border-radius: 2px;
      border-width: 2px;
      font-family: var(--display-font);
    }
  
    .gr-hero__editors {
      @media (max-width: 36em) {
        display: none;
      }
    }

    .gr-hero__editors-title {
      font-weight: 700;
    }

  .gr-logos-container {
    @media (min-width: 74em) {
      width: 640px;
      position: fixed;
      top: 640px;
      left: 0;
      background-color: var(--white-color);
      box-sizing: border-box;
    }
  }

  .gr-logos {
    display: flex;
    flex-flow: row nowrap;
    gap: var(--s2);
    justify-content: center;
    align-items: center;
    padding-block: var(--s1);
  }

  h2.gr-title {
    font-size: 1.5em;
    margin-bottom: var(--s1);
  }

  .gr-content {
    padding-block: var(--s2);
    border-top: 1px solid var(--base-color-20);
    @media (min-width: 74em) {
      padding-left: calc(640px + var(--s1));
    }
    p {
      margin-bottom: var(--s0);
      font-size: 1em;
    }
  }

  .footer {
    background-color: var(--base-color);
    color: var(--white-color);
  }

    .copy {
      text-align: center;
      padding-block: var(--s0);
      a {
        color: var(--white-color);
        font-weight: 700;
      }
    }
</style>
