<template>
  <div class="profile">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Profile</h2>
        </div>
      </div>
      <div class="row">
        <div class="column">
          <div class="detail">Name: Worapong Malaiwong</div>
          <div class="detail">Education: King Mongkut's Institute of Technology Ladkrabang</div>
          <div class="sub-detail">Bachelor of Science (Information Technology)</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Profile'
}
</script>

<style scoped lang="scss">
$eng_font: "PT Mono", monospace;

h2 {
  font-family: $eng_font;
  text-align: center;
  font-size: 2.25em;
}

.detail {
  font-family: $eng_font;
  font-size: 1.4em;
}

.sub-detail {
  font-family: $eng_font;
  font-size: 1.2em;
  margin-left: 7.8em;
}
</style>
