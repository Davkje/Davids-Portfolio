<script setup lang="ts"></script>

<template>
  <div class="contact-section">
    <div class="contact-container">
      <div class="contacts">
        <h2>Get in touch!</h2>
        <p>+46 (0) 73 529 2002</p>
        <a href="mailto:david.kjellstrand@gmail.com">david.kjellstrand@gmail.com</a>
      </div>
      <div class="links-container">
        <a
          href="https://www.linkedin.com/in/david-kjellstrand-b6760113a/"
          target="_blank"
          rel="noopener noreferrer"
          >LinkedIn</a
        >
        <a href="https://github.com/Davkje" target="_blank" rel="noopener noreferrer">Github</a>
        <a href="assets/david-kjellstrand-cv.pdf" download>Download CV</a>
      </div>
      <p class="small-text">
        This website was created fully by me, David. I used Vue as my framwork but other than that
        its basic html and css.
      </p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.contact-section {
  color: black;
  font-size: 1.4rem;
  width: 100%;
  height: 100%;
  min-height: 500px;
  background-color: #000000;
  display: flex;
  justify-content: center;
  align-items: center;
  background-size: cover;
  .contact-container {
    background-color: #ffe572;
    background: radial-gradient(circle, var(--c-light-yellow), var(--c-dark-yellow));
    border-radius: 10px;
    width: 80vw;
    padding: 3rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    .contacts {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 1rem;
    }
    .links-container {
      display: flex;
      flex-wrap: wrap;
      margin: auto;
      max-width: 500px;
      justify-content: space-evenly;
      margin-top: 1rem;
      gap: 1rem;
    }
    .small-text {
      color: rgba(0, 0, 0, 0.716);
      padding-top: 1rem;
      font-size: 0.8rem;
      text-align: center;
    }
  }
}
</style>
