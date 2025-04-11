<script setup lang="ts"></script>

<template>
  <div class="about-section">
    <h2>About Me</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat sunt rem error dolores.
      Assumenda perferendis quia similique quibusdam ratione dolorem recusandae ex error rerum
      alias, nesciunt harum architecto cupiditate dignissimos?
    </p>
  </div>
</template>

<style scoped lang="scss">
.about-section {
  width: 100%;
  height: 700px;
  padding: 1rem;
  background-color: #f47d7d;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: black;
  p {
    max-width: 70vw;
    text-align: center;
    margin: 0 auto;
    font-size: 1.2rem;
  }
}
</style>
