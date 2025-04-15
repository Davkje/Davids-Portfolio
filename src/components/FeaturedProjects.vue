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
        <img src="../assets/images/tictactoe-preview.png" alt="Preview of the Dino Game" />
        <h3>Tic Tac Toe</h3>
        <p>
          A simple yet fleshed out game of Tic Tac Toe. The game is built with TypeScript, HTML and
          SCSS. It has a working gameloop, light and dark mode and audio with a volume slider. Check
          it out!
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
        <img src="../assets/images/cookies-preview.png" alt="Preview of the Dino Game" />
        <h3>Cookies Webshop</h3>
        <p>
          My first website using JavaScript! The website is a simple webshop where you can purchase
          cookies. The website is built with JavaScript, HTML and SCSS. It has a working cart,
          checkout-form with validation and filtering for browsing the cookies!
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
    </section>
  </div>
</template>

<style scoped lang="scss">
.projects-section {
  width: 100%;
  min-width: 500px;
  padding: 1rem;
  background: linear-gradient(to bottom, #ffffff, #000000);
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
      width: clamp(500px, 700px, 100%);
      height: 100%;
      background: linear-gradient(to bottom, #ffffff, #eaeaea);
      border-radius: 10px;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.165);
      img {
        width: 100%;
        height: clamp(200px, 400px, 500px);
        object-fit: cover;
        border-radius: 10px;
      }
      h3 {
        margin: 0.5rem 0;
        font-size: 1.6rem;
      }
      p {
        font-size: 1.2rem;
        line-height: 1.5;
      }
      .tech-container {
        display: flex;
        gap: 0.5rem;
        margin-top: 1rem;
        .tech-tag {
          background-color: rgb(255, 229, 114);
          padding: 0.5rem;
          border-radius: 6px;
          cursor: default;
          transition: background-color 0.1s ease-in-out;
          &:hover {
            background-color: rgb(255, 237, 158);
          }
        }
      }
      .project-buttons {
        display: flex;
        gap: 0.5rem;
        margin-top: 1rem;
        .link-btn {
          background-color: rgb(255, 255, 252);
          color: black;
          font-size: 1.1rem;
          padding: 0.8rem 2rem;
          border-radius: 8px;
          border: none;
          cursor: pointer;
          &:hover {
            background-color: rgb(228, 228, 228);
          }
        }
      }
    }
  }
}
</style>
