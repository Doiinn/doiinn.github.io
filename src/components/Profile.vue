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
          <div class="group">
            <div class="title">Name:</div>
            <div class="detail">Worapong Malaiwong</div>
          </div>
          <div class="group">
            <div class="title">Education:</div>
            <div class="detail">King Mongkut's Institute of Technology Ladkrabang</div>
            <div class="sub-detail">(Aug 2014 - Jun 2018)</div>
            <div class="sub-detail">Bachelor of Science (Information Technology)</div>
          </div>
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

.profile {
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
