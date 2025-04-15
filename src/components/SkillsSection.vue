<script setup lang="ts"></script>

<template>
  <div class="skills-section">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill-column">
        <h4>Code</h4>
        <ul>
          <li>Html5</li>
          <li>Css3</li>
          <li>Sass</li>
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>Vue</li>
          <li>Vite</li>
          <li>GSAP</li>
          <li>SQL</li>
          <li>Markdown</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>Toolbox</h4>
        <ul>
          <li>VS Code</li>
          <li>Figma</li>
          <li>Adobe Suite</li>
          <li>Github</li>
          <li>Prettier</li>
          <li>ESLint</li>
          <li>npm/pnpm</li>
          <li>Lighthouse</li>
          <li>Teams</li>
          <li>Slack</li>
          <li>Logic Pro</li>
          <li>Wwise</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>More</h4>
        <ul>
          <li>UI/UX Basics</li>
          <li>Wireframing</li>
          <li>Prototyping</li>
          <li>Design Systems</li>
          <li>SEO</li>
          <li>Agile/Scrum</li>
          <li>Accesibility</li>
          <li>Responsive Design</li>
          <li>Cross-Browser Compatibility</li>
          <li>Working with API's</li>
          <li>Team Communication (Slack, Trello)</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>Upcoming</h4>
        <ul>
          <li>React</li>
          <li>Three.js</li>
          <li>API development</li>
          <li>Testing</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.skills-section {
  width: 100%;
  min-height: 500px;
  color: black;
  background-color: rgb(0, 0, 0);
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
  h2 {
    color: rgb(255, 255, 255);
  }
  .skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    gap: 1rem;
    margin-top: 1rem;
    .skill-column {
      width: 200px;
      border: solid rgb(248, 248, 248) 2px;
      background: linear-gradient(to bottom, #ffffff, #d8d8d8);
      border-radius: 10px;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      ul {
        list-style-type: none;
        padding: 0;
        li {
          font-size: 1.2rem;
          margin-bottom: 0.5rem;
        }
      }
    }
  }
}
</style>
