<script setup lang="ts"></script>

<template>
  <div class="hero-section">
    <div class="hero-container">
      <div class="top-section">
        <img
          class="profile-img"
          src="../assets/images/small_profile_pic.jpg"
          alt="Black and white image of David Kjellstrand"
          height="2048"
          width="1536"
          loading="lazy"
        />
        <div class="top-right-section">
          <h1>David Kjellstrand</h1>
          <h2>Front End Developer</h2>
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
        <a href="#featured-projects">Go to portfolio</a>
      </div>
    </div>
    <img
      class="small-profile-img"
      src="../assets/images/small_profile_pic.jpg"
      alt="Black and white image of David Kjellstrand"
      height="2048"
      width="1536"
      loading="lazy"
    />
  </div>
</template>

<style scoped lang="scss">
.hero-section {
  color: var(--c-black);
  width: 100%;
  min-height: 650px;
  background-image: url('../assets/images/bg.jpg');
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 1rem;
  background-size: cover;
  padding: 2rem 1rem;
  .hero-container {
    background: var(--gradient-white-soft);
    width: clamp(300px, 90%, 1100px);
    height: 100%;
    padding: 2rem;
    border-radius: 8px;
    .top-section {
      width: 100%;
      height: 100%;
      display: flex;
      align-items: center;
      gap: 1.5rem;
      .profile-img {
        width: 20%;
        height: 20%;
        aspect-ratio: 1/1;
        object-fit: cover;
        border-radius: 50%;
      }
      .top-right-section {
        height: 100%;
        display: flex;
        justify-content: flex-start;
        flex-direction: column;
        h1 {
          line-height: normal;
        }
        h2 {
          font-weight: 500;
          line-height: normal;
        }
      }
    }
    p {
      margin-top: 1rem;
    }
    .links-container {
      display: flex;
      margin: auto;
      max-width: 500px;
      justify-content: space-between;
      margin-top: 1rem;
    }
    .go-to-portfolio {
      margin-top: 1rem;
      display: flex;
      justify-content: center;
      align-items: center;
      a {
        color: black;
        background-color: var(--c-yellow);
        padding: 0.5rem 1.5rem;
        border-radius: 8px;
        &:hover {
          background-color: var(--c-light-yellow);
        }
      }
    }
  }
  .small-profile-img {
    display: none;
  }
}

@media screen and (max-width: 550px) {
  .hero-section .hero-container .top-section .profile-img {
    display: none;
  }
  .hero-section .small-profile-img {
    display: block;
    width: clamp(300px, 90%, 1100px);
    border-radius: 8px;
    height: 45vw;
    object-fit: cover;
  }
}
</style>
