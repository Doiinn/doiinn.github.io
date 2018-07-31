<template>
  <div class="experiences">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Experiences</h2>
        </div>
      </div>
      <div class="row">
        <div class="column column-25">
          <div class="title">Fungjai Co., Ltd</div>
          <div class="sub-detail">13 June - 31 July 2016</div>
        </div>
        <div class="column column-75">
          <div class="detail">Frontend Developer Intern</div>
          <div class="sub-detail">- Upgraded Fungjai.com's website from Angular 2.0 RC4 to 4.x series</div>
          <div class="sub-detail">- Fixed the bug, clean up and refactor code</div>
          <div class="sub-detail">- Config server-side rendering (Angular Universal)</div>
          <div class="sub-detail">- Config webpack for production</div>
          <div class="sub-detail">- Blog for about my work <a href="https://medium.com/fungjai/moving-fungjai-to-angular-4-57b9cf184f76">Click!</a></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Experiences'
}
</script>

<style scoped lang="scss">
$eng_font: "PT Mono", monospace;

.experiences {
  padding-bottom: 8em;
}
a {
  text-decoration: none;
  color:#29b777;
}

a:visited {
  text-decoration: none;
  color:#29b777;
}

h2 {
  font-family: $eng_font;
  text-align: center;
  font-size: 2.25em;
}

.title, .detail,  {
  font-family: $eng_font;
  font-size: 1.4em;
}

.sub-detail {
  font-family: $eng_font;
  font-size: 1em;
}
</style>
