<template>
  <div class="skills">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Skliis</h2>
        </div>
      </div>
      <div class="row">
        <div class="column">
          <div class="group">
            <div class="title">Language:</div>
            <div class="detail">Thai (Native Speaker), English (Intermediate)</div>
          </div>
          <div class="group">
            <div class="title">Programming:</div>
            <div class="detail">Basic </div>
          </div>
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

.title {
  font-family: $eng_font;
  font-size: 1.4em;
  display: inline-block;
  width: 8em;
}

.detail {
  font-family: $eng_font;
  font-size: 1.4em;
  display: inline-block;
}

.sub-detail {
  font-family: $eng_font;
  font-size: 1.2em;
  margin-left: 7.8em;
}
</style>
