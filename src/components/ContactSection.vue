<script setup lang="ts"></script>

<template>
  <div class="contact-section">
    <div class="contact-container">
      <div class="contacts">
        <h2>Get in touch!</h2>
        <p>+46 (0) 73 529 2002</p>
        <p>david.kjellstrand@gmail.com</p>
      </div>
      <div class="links-container">
        <a href="">LinkedIn</a>
        <a href="">Github</a>
        <a href="">Instagram</a>
        <a href="">Email</a>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.contact-section {
  color: black;
  font-size: 1.4rem;
  width: 100%;
  height: 700px;
  background-color: #000000;
  display: flex;
  justify-content: center;
  align-items: center;
  background-size: cover;
  .contact-container {
    background-color: rgb(255, 255, 255);
    width: 80%;
    max-width: 80%;
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
      background-color: rgba(0, 0, 0, 0.183);
      display: flex;
      margin: auto;
      max-width: 500px;
      justify-content: space-between;
      margin-top: 1rem;
      a {
        color: black;
        text-decoration: none;
        font-size: 1.2rem;
        &:hover {
          text-decoration: underline;
        }
      }
    }
  }
}
</style>
