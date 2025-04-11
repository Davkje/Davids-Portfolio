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
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>React</li>
          <li>Vue</li>
          <li>Markdown</li>
          <li>SQL</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>Toolbox</h4>
        <ul>
          <li>Html5</li>
          <li>Css3</li>
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>React</li>
          <li>Vue</li>
          <li>Markdown</li>
          <li>SQL</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>More</h4>
        <ul>
          <li>Html5</li>
          <li>Css3</li>
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>React</li>
          <li>Vue</li>
          <li>Markdown</li>
          <li>SQL</li>
        </ul>
      </div>
      <div class="skill-column">
        <h4>Upcoming</h4>
        <ul>
          <li>Html5</li>
          <li>Css3</li>
          <li>JavaScript</li>
          <li>TypeScript</li>
          <li>React</li>
          <li>Vue</li>
          <li>Markdown</li>
          <li>SQL</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.skills-section {
  width: 100%;
  min-height: 600px;
  color: black;
  background-color: rgb(226, 186, 224);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  h2 {
    font-size: 2rem;
    font-weight: bold;
  }
  .skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    margin-top: 1rem;
    .skill-column {
      width: 200px;
      background-color: lightgray;
      border-radius: 10px;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      h4 {
        font-size: 1.5rem;
        margin-bottom: 0.5rem;
      }
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
