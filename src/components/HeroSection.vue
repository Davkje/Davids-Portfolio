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
        <a
          href="https://www.linkedin.com/in/david-kjellstrand-b6760113a/"
          target="_blank"
          rel="noopener noreferrer"
          >LinkedIn</a
        >
        <a href="https://github.com/Davkje" target="_blank" rel="noopener noreferrer">Github</a>
        <a href="mailto:david.kjellstrand@gmail.com">Email</a>
        <a href="https://www.instagram.com/dk.strand/" target="_blank" rel="noopener noreferrer"
          >Instagram</a
        >
      </div>
      <div class="go-to-portfolio">
        <a href="#featured-projects">See my portfolio below</a>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.hero-section {
  color: black;
  width: 100%;
  height: 700px;
  background-image: url('../assets/images/profile_pic.jpg');
  display: flex;
  justify-content: center;
  align-items: center;
  background-size: cover;
  .hero-container {
    background-color: rgb(237, 237, 237);
    width: 80%;
    max-width: 1100px;
    margin: auto;
    padding: 2rem;
    border-radius: 8px;
    .top-section {
      width: 100%;
      height: 100%;
      display: flex;
      align-items: center;
      gap: 1rem;
      .profile-img {
        width: 20%;
        height: 20%;
        aspect-ratio: 1/1;
        object-fit: cover;
        border-radius: 50%;
      }
      .top-right-section {
        color: black;
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        h1 {
          line-height: normal;
        }
        h2 {
          font-weight: 100;
        }
      }
    }
    p {
      color: black;
      line-height: 1.5rem;
      margin-top: 1rem;
    }
    .links-container {
      display: flex;
      margin: auto;
      max-width: 500px;
      justify-content: space-between;
      margin-top: 1rem;
      a {
        color: black;
        text-decoration: none;
        &:hover {
          text-decoration: underline;
        }
      }
    }
    .go-to-portfolio {
      margin-top: 1rem;
      display: flex;
      justify-content: center;
      align-items: center;
      a {
        color: black;
      }
    }
  }
}
</style>
