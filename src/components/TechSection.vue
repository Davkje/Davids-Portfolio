<script setup lang="ts"></script>

<template>
  <div class="tech-section">
    <h2>Tech</h2>
    <div class="tech-stack">
      <p class="tech">Html</p>
      <p class="tech">Css/Scss</p>
      <p class="tech">JavaScript</p>
      <p class="tech">TypeScript</p>
      <p class="tech">Vite</p>
      <p class="tech">Vue</p>
      <p class="tech">React</p>
      <p class="tech">Node</p>
      <p class="tech">Express</p>
      <p class="tech">Git</p>
      <p class="tech">Github</p>
      <p class="tech">Figma</p>
      <p class="tech">Adobe</p>
      <p class="tech">Logic Pro</p>
      <p class="tech">Wwise</p>
      <p class="tech">Unreal Engine</p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.tech-section {
  width: 100%;
  height: 400px;
  background-color: rgb(255, 255, 255);
  color: black;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    margin-top: 1rem;
    .tech {
      background-color: rgb(248, 248, 248);
      padding: 0.5rem 1rem;
      border-radius: 8px;
      cursor: default;
      transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
      &:hover {
        scale: 1.1;
        box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.127);
      }
    }
  }
}
</style>
