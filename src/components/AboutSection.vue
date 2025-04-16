<script setup lang="ts">
import { useRouter } from 'vue-router'
import { nextTick } from 'vue'

const router = useRouter()

const goToFeaturedProjects = () => {
  router.push({ path: '/', hash: '#featured-projects' }).then(() => {
    setTimeout(() => {
      const el = document.querySelector('#featured-projects')
      if (el) {
        el.scrollIntoView({ behavior: 'smooth' })
      }
    }, 100)
  })
}
</script>

<template>
  <div class="about-section">
    <div>
      <h2>Who?</h2>
      <p>
        Hi! I'm David Kjellstrand! An aspiring Front End Developer and former writer/producer with a
        passion for all things creative! During the past 8 years as a freelancing audio creator I've
        honed my creative, social and technical skills through working on multiple projects for
        artists, labels, commercials and tv.
      </p>
    </div>
    <div>
      <h2>What?</h2>
      <p>
        What am I doing? We'll I'm trying a new path, moving away from music to coding, by studying
        Front End Developement at Medieinstitutet and I'm looking for an internship for late 2025
        and spring of 2026!
      </p>
    </div>
    <div>
      <h2>Where?</h2>
      <p>Stockholm is home! Been spenindg the past year outside Karlstad while studying though!</p>
    </div>
    <div>
      <h2>Why...</h2>
      <p>
        ... dont you check out some of my work in my
        <a href="#" @click.prevent="goToFeaturedProjects">portfolio</a> or if you already have,
        listen to some music I've released over the years? Have a good one!
      </p>
    </div>
    <iframe
      class="spotify-player"
      style="border-radius: 12px"
      src="https://open.spotify.com/embed/playlist/36iVvde48wbmv5WinHK1Y6?utm_source=generator&theme=0"
      frameBorder="0"
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      loading="lazy"
    ></iframe>
  </div>
</template>

<style scoped lang="scss">
.about-section {
  width: 100%;
  min-height: 94vh;
  padding: 1rem;
  background-color: var(--c-white);
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  color: black;
  div {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 1rem;
    h2 {
      font-size: clamp(2rem, 5vw, 3rem);
      margin-bottom: 1rem;
    }
    p {
      width: clamp(200px, 70vw, 900px);
      text-align: center;
      margin: 0 auto;
      font-size: clamp(1rem, 2vw, 1.2rem);
    }
    a {
      font-weight: bold;
      cursor: pointer;
    }
  }

  .spotify-player {
    margin-top: 3rem;
    width: clamp(30px, 90%, 500px);
    height: 200px;
    border-radius: 12px;
  }
}
</style>
