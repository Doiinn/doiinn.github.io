<template>
  <div class="container">

  <div class="row">
    <div class="column">
      <h1>This is</h1>
    </div>
  </div>

  <div class="row">
    <div class="column">
        <h1 class="text-typing">Worapong's Portfolio</h1>
    </div>
  </div>

  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@keyframes typing { from { width: 0; } }
@keyframes blink-caret { 50% { border-color: transparent; } }

.container {
  font-family: 'PT Mono', monospace;
  padding: 24rem 2rem;
}

.text-typing {
  border-right: .075em solid black;
  width: 11.7em;
  white-space: nowrap;
  overflow: hidden;
  animation: typing 7.5s steps(20, end), blink-caret .5s step-end infinite alternate;
}

</style>
