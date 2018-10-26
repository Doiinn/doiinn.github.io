<template>
  <div class="works">
    <div class="container">
      <div class="row">
        <div class="column">
          <h2>Works</h2>
        </div>
      </div>
      <div class="row">
        <div class="column column-33">
          <img class="card-img-top" :src="pic" />
          <div class="card-body">
            <h5 class="card-title">BNK Memorize</h5>
            <p class="card-text">Guess who is the picture from BNK48 Members. Create using by React</p>
            <a href="https://doiinn.github.io/bnk-memorize" class="button button-green">Click to play</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import pic from '@/assets/bnk-memorize.png'

export default {
  name: 'Works',
  data: () => {
    return {
      pic: pic
      }
    }
}
</script>

<style scoped lang="scss">
$eng_font: "PT Mono", monospace;

.works {
  padding-bottom: 8em;
}
a {
  text-decoration: none;
  color: #29b777;
  font-size: 0.75em;
}

a:visited {
  text-decoration: none;
  color: #29b777;
}

a:hover {
  text-decoration: none;
  color: white;
}

h2 {
  font-family: $eng_font;
  text-align: center;
  font-size: 2.25em;
}

.card-title {
  font-family: $eng_font;
  font-size: 1.4em;
  text-align: center;
}

.sub-detail {
  font-family: $eng_font;
  font-size: 1em;
}

.button-green {
  background-color: transparent;
  border-color: #29b777;
  display: block;
}

.button-green:hover {
  background-color: #29b777;
}
</style>
