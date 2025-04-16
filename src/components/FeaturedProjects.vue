<script setup lang="ts"></script>

<template>
  <div id="featured-projects" class="projects-section">
    <h2>Featured Projects</h2>
    <section class="projects">
      <div class="project-container">
        <img src="../assets/images/dino_game.png" alt="Preview of the Dino Game" />
        <h3>Davids Dino Game</h3>
        <p>
          A small game you might recognize where you control a dinosaur and try to avoid obstacles.
          The game is built using Vue, TypeScript, HTML and all assets where created by me including
          the audio. Try it and you will learn more about it as you play!
        </p>
        <div class="tech-container">
          <span class="tech-tag">TypeScript</span>
          <span class="tech-tag">Vue</span>
          <span class="tech-tag">Html</span>
          <span class="tech-tag">Scss</span>
          <span class="tech-tag">Game</span>
          <span class="tech-tag">Audio</span>
        </div>
        <div class="project-buttons">
          <a
            class="link-btn"
            href="https://davkje.github.io/jumping-game/"
            target="_blank"
            rel="noopener noreferrer"
            >Live Demo</a
          >
          <a
            class="link-btn"
            href="https://github.com/Davkje/jumping-game"
            target="_blank"
            rel="noopener noreferrer"
            >Github</a
          >
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/tictactoe-preview.png" alt="Preview of the Tic Tac Toe Game" />
        <h3>Tic Tac Toe</h3>
        <p>
          A simple yet fleshed out game of Tic Tac Toe! The game is built with TypeScript, HTML and
          SCSS. It has a working gameloop, light and dark mode and adaptive audio with a volume
          slider. Check it out!
        </p>
        <div class="tech-container">
          <span class="tech-tag">TypeScript</span>
          <span class="tech-tag">Html</span>
          <span class="tech-tag">Scss</span>
          <span class="tech-tag">Game</span>
          <span class="tech-tag">Audio</span>
        </div>
        <div class="project-buttons">
          <a
            class="link-btn"
            href="https://davkje.github.io/tic-tac-toe-game/"
            target="_blank"
            rel="noopener noreferrer"
            >Live Demo</a
          >
          <a
            class="link-btn"
            href="https://github.com/Davkje/tic-tac-toe-game"
            target="_blank"
            rel="noopener noreferrer"
            >Github</a
          >
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/cookies-preview.png" alt="Preview of the Cookies Webshop" />
        <h3>Cookies Webshop</h3>
        <p>
          My first website using JavaScript! The website is a simple webshop where you can purchase
          cookies. The website is built with JavaScript, HTML and SCSS. It has a working cart,
          checkout-form, validation and filtering for browsing!
        </p>
        <div class="tech-container">
          <span class="tech-tag">Javascript</span>
          <span class="tech-tag">Html</span>
          <span class="tech-tag">Scss</span>
          <span class="tech-tag">Webshop</span>
          <span class="tech-tag">RegEx</span>
          <span class="tech-tag">Filtering</span>
        </div>
        <div class="project-buttons">
          <a
            class="link-btn"
            href="https://davkje.github.io/Davids-Cookies/"
            target="_blank"
            rel="noopener noreferrer"
            >Live Demo</a
          >
          <a
            class="link-btn"
            href="https://github.com/Davkje/Davids-Cookies"
            target="_blank"
            rel="noopener noreferrer"
            >Github</a
          >
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/quiz-preview.png" alt="Preview of the Ballerina Quiz" />
        <h3>Ballerina Quiz</h3>
        <p>
          A small group project where we created a quiz about "Ballerinas" (a Swedish cookie). Its
          created with TypeScript and a big focus was working together using the Agile methodology.
          The quiz has a timer, scoresystem and randomized questions.
        </p>
        <div class="tech-container">
          <span class="tech-tag">TypeScript</span>
          <span class="tech-tag">Html</span>
          <span class="tech-tag">Scss</span>
          <span class="tech-tag">Quiz</span>
          <span class="tech-tag">Agile</span>
          <span class="tech-tag">Arrays</span>
        </div>
        <div class="project-buttons">
          <a
            class="link-btn"
            href="https://medieinstitutet.github.io/fed24d-js-intro-inl-2-quiz-ballerinas/"
            target="_blank"
            rel="noopener noreferrer"
            >Live Demo</a
          >
          <a
            class="link-btn"
            href="https://github.com/medieinstitutet/fed24d-js-intro-inl-2-quiz-ballerinas"
            target="_blank"
            rel="noopener noreferrer"
            >Github</a
          >
        </div>
      </div>
      <div class="project-container">
        <img
          src="../assets/images/codesmell-preview.png"
          alt="Preview of the Code Smells assignment"
        />
        <h3>Code Smells</h3>
        <p>
          This was a school assignment where we had to clean up a codebase with a lot of "Code
          Smells". It's a simple layout where it fetches and displays podcasts. This was also the
          first time I worked with API's.
        </p>
        <div class="tech-container">
          <span class="tech-tag">TypeScript</span>
          <span class="tech-tag">API</span>
          <span class="tech-tag">Refactor</span>
          <span class="tech-tag">Bugfixing</span>
        </div>
        <div class="project-buttons">
          <a
            class="link-btn"
            href="https://medieinstitutet.github.io/fed24d-arbetsmetodik-inl-1-Davkje/"
            target="_blank"
            rel="noopener noreferrer"
            >Live Demo</a
          >
          <a
            class="link-btn"
            href="https://github.com/Medieinstitutet/fed24d-arbetsmetodik-inl-1-Davkje"
            target="_blank"
            rel="noopener noreferrer"
            >Github</a
          >
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped lang="scss">
.projects-section {
  width: 100%;
  padding: 1rem;
  background: linear-gradient(to bottom, var(--c-white), var(--c-black));
  display: flex;
  flex-direction: column;
  align-items: center;

  .projects {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    width: 100%;
    height: 100%;
    margin: 0 auto;
    padding: 1rem;

    .project-container {
      color: black;
      width: clamp(400px, 600px, 100%);
      height: 100%;
      max-height: 100vh;
      background: var(--gradient-white-soft);
      border-radius: 10px;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      box-shadow: 0 4px 10px var(--c-divider-light-1);
      img {
        width: 100%;
        height: clamp(200px, 45vw, 420px);
        object-fit: cover;
        border-radius: 10px;
      }
      h3 {
        margin: 0.5rem 0;
        font-size: 1.6rem;
      }
      p {
        font-size: clamp(1rem, 1.5vw, 1.2rem);
        line-height: 1.5;
      }
      .tech-container {
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
        margin-top: 1.5rem;
        .tech-tag {
          background-color: var(--c-white);
          padding: 0.5rem;
          border-radius: 8px;
          cursor: default;
          transition: background-color 0.1s ease-in-out;
        }
      }
      .project-buttons {
        display: flex;
        gap: 0.5rem;
        margin-top: 1rem;
        .link-btn {
          background-color: var(--c-yellow);
          color: black;
          font-size: 1.1rem;
          padding: 0.8rem 2rem;
          border-radius: 8px;
          border: none;
          cursor: pointer;
          transition: background-color 0.2s ease;
          &:hover {
            background-color: var(--c-light-yellow);
          }
        }
      }
    }
  }
}

@media screen and (max-width: 550px) {
  .projects-section .projects .project-container .project-buttons {
    justify-content: center;
  }
}
</style>
