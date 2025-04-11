<script setup lang="ts"></script>

<template>
  <div class="tech-section">
    <h2>Tech</h2>
    <div class="tech-stack">
      <p>HTML</p>
      <p>CSS</p>
      <p>JavaScript</p>
      <p>TypeScript</p>
      <p>Vite</p>
      <p>Vue.js</p>
      <p>React.js</p>
      <p>Node.js</p>
      <p>Express.js</p>
      <p>Git</p>
      <p>Figma</p>
      <p>Adobe</p>
      <p>Logic Pro</p>
      <p>Wwise</p>
      <p>Unreal Engine</p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.tech-section {
  width: 100%;
  height: 500px;
  background-color: aquamarine;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  h2 {
    color: black;
    font-size: 2rem;
    font-weight: bold;
  }
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    margin-top: 1rem;
    p {
      color: black;
    }
  }
}
</style>
