<template>
  <div class="skills">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Skliis</h2>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Language:</div>
        </div>
        <div class="column column-75">
          <div class="detail">Thai (Native Speaker), English (Intermediate)</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Programming:</div>
        </div>
        <div class="column column-75">
          <div class="detail">Javascript, Typescript, Java, Python, C#, PHP, C and C++</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Mobile Platform:</div>
        </div>
        <div class="column column-75">
          <div class="detail">Android</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Web Technology:</div>
        </div>
        <div class="column column-75">
          <div class="detail">Frontend - HTML, CSS, Angular, React, Vue.js and JQuery</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25"></div>
        <div class="column column-75">
          <div class="sub-detail">Backend - Node.js, Express and Spring Boot</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Database:</div>
        </div>
        <div class="column column-75">
          <div class="detail">MySQL (or MariaDB), MongoDB and Firebase realtime database (a bit of knowledge)</div>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Other:</div>
        </div>
        <div class="column column-75">
          <div class="detail">Docker, Git and Basic Linux Command</div>
        </div>
      </div>
      <p>
      <div class="row">
        <div class="column">
          <div class="title">What language (or framework) doesn't in a list. I'm always ready to learn.</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Skills'
}
</script>

<style scoped lang="scss">
$eng_font: "PT Mono", monospace;

a {
  text-decoration: none;
  color:#29b777;
}

a:visited {
  text-decoration: none;
  color:#29b777;
}

.skills {
  padding-bottom: 8em;
}

h2 {
  font-family: $eng_font;
  text-align: center;
  font-size: 2.25em;
}

.title, .detail, .sub-detail {
  font-family: $eng_font;
  font-size: 1.4em;
}
</style>
