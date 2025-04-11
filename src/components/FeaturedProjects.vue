<script setup lang="ts"></script>

<template>
  <div class="projects-section">
    <h2>Featured Projects</h2>
    <section class="projects">
      <div class="project-container">
        <img src="../assets/images/profile_pic.JPG" alt="Project image" />
        <h3>Project</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt
          ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
        <div class="tech-container">
          <span>Html</span>
          <span>Css</span>
          <span>JavaScript</span>
        </div>
        <div class="project-buttons">
          <button>Demo</button>
          <button>Github</button>
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/profile_pic.JPG" alt="Project image" />
        <h3>Project</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt
          ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
        <div class="tech-container">
          <span>Html</span>
          <span>Css</span>
          <span>JavaScript</span>
        </div>
        <div class="project-buttons">
          <button>Demo</button>
          <button>Github</button>
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/profile_pic.JPG" alt="Project image" />
        <h3>Project</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt
          ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
        <div class="tech-container">
          <span>Html</span>
          <span>Css</span>
          <span>JavaScript</span>
        </div>
        <div class="project-buttons">
          <button>Demo</button>
          <button>Github</button>
        </div>
      </div>
      <div class="project-container">
        <img src="../assets/images/profile_pic.JPG" alt="Project image" />
        <h3>Project</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt
          ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
        <div class="tech-container">
          <span>Html</span>
          <span>Css</span>
          <span>JavaScript</span>
        </div>
        <div class="project-buttons">
          <button>Demo</button>
          <button>Github</button>
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
  background-color: rgb(237, 215, 117);
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
    background-color: rgb(237, 215, 117);

    .project-container {
      color: black;
      width: clamp(500px, 700px, 100%);
      height: 100%;
      background-color: lightgray;
      border-radius: 10px;
      padding: 1rem;
      display: flex;
      flex-direction: column;
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
        span {
          background-color: rgb(237, 215, 117);
          padding: 0.5rem;
          border-radius: 6px;
        }
      }
      .project-buttons {
        display: flex;
        gap: 0.5rem;
        margin-top: 1rem;
        button {
          background-color: rgb(255, 255, 252);
          font-size: 1.2rem;
          padding: 1rem 2rem;
          border-radius: 8px;
          border: none;
          cursor: pointer;
          &:hover {
            background-color: rgb(200, 200, 200);
          }
        }
      }
    }
  }
}
</style>
