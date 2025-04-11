<script setup lang="ts"></script>

<template>
  <div class="hero-section">
    <div class="hero-container">
      <div class="top-section">
        <img
          class="profile-img"
          src="../assets/images/profile_pic.JPG"
          alt="Black and white image of David Kjellstrand"
          height="2048"
          width="1536"
          loading="lazy"
        />
        <div class="top-right-section">
          <h1>David Kjellstrand</h1>
          <h2>Front End Developer</h2>
          <p>+ Digital Designer</p>
        </div>
      </div>
      <p>
        Aspiring Front End Developer and former writer/producer with a creative mindset and a
        passion for creating visually appealing and user-friendly web applications. Seeking a
        challenging internship to further develop my skills in modern front end development and
        contribute to innovative and interesting projects. During the past 8 years as a signed and
        freelancing audio creator I've honed my creative and technical abilities through working on
        multiple projects for artists, labels, commercials and tv.
      </p>
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
.hero-section {
  width: 100%;
  height: 700px;
  background-image: url('../assets/images/profile_pic.jpg');
  display: flex;
  justify-content: center;
  align-items: center;
  background-size: cover;
  .hero-container {
    background-color: aliceblue;
    width: 80%;
    max-width: 800px;
    margin: auto;
    padding: 1rem;
    .top-section {
      background-color: rgba(0, 0, 0, 0.11);
      padding: 1rem;
      width: 100%;
      display: flex;
      align-items: center;
      gap: 1rem;
      .profile-img {
        width: 30%;
        height: 30%;
        aspect-ratio: 1/1;
        object-fit: cover;
        border-radius: 50%;
      }
      .top-right-section {
        color: black;
        background-color: rgba(0, 0, 0, 0.11);
        display: flex;
        flex-direction: column;
        justify-content: center;
      }
    }
    p {
      color: black;
      font-size: 1.2rem;
      line-height: 1.5rem;
      margin-top: 1rem;
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
