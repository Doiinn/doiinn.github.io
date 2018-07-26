<template>
  <div class="skills">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Skliis</h2>
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
  width: 6.7em;
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
