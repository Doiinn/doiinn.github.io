<template>
  <div id="home">
    <Header/>
    <Profile/>
    <Skills/>
    <Experiences/>
    <Works/>
    <div class="container">
      <div class="row">
        <div class="column">
          <p>© 2018 WORAPONG MALAIWONG</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Profile from '@/components/Profile.vue'
import Skills from '@/components/Skills.vue'
import Experiences from '@/components/Experiences.vue'
import Works from '@/components/Works.vue'
import ScrollReveal from 'scrollreveal'

const sr = ScrollReveal({ reset: false })

export default {
  name: 'home',
  components: {
    Header,
    Profile,
    Skills,
    Experiences,
    Works
  },
  mounted: () => {
    sr.reveal('.profile', { duration: 1500, easing: 'cubic-bezier(0.6, 0.2, 0.1, 1)', scale: 0.5 })
    sr.reveal('.skills', { duration: 1500, easing: 'cubic-bezier(0.6, 0.2, 0.1, 1)', scale: 0.5 })
    sr.reveal('.experiences', { duration: 1500, easing: 'cubic-bezier(0.6, 0.2, 0.1, 1)', scale: 0.5 })
    sr.reveal('.works', { duration: 1500, easing: 'cubic-bezier(0.6, 0.2, 0.1, 1)', scale: 0.5 })
  }
}
</script>

<style scoped lang="scss">
  #home {
    font-family: "PT Mono", monospace;
    padding-bottom: 1em;
  }
</style>
