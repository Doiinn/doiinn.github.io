<template>
  <div class="container">

  <div class="row">
    <div class="column">
      <h1>This is</h1>
    </div>
  </div>

  <div class="row">
    <div class="column">
      <div class="type-js headline">
        <h1 class="text-js">Worapong's Portfolio</h1>
      </div>
    </div>
  </div>

  </div>
</template>

<script>
import JQuery from 'jquery'
let $ = JQuery

const autoType = (elementClass, typingSpeed) => {
  var thhis = $(elementClass)
  thhis.css({
    'position': 'relative',
    'display': 'inline-block'
  })
  thhis.prepend('<div class="cursor" style="right: initial; left:0;"></div>')
  thhis = thhis.find('.text-js')
  var text = thhis.text().trim().split('')
  var amntOfChars = text.length
  var newString = ''
  thhis.text('|')
  setTimeout(function () {
    thhis.css('opacity', 1)
    thhis.prev().removeAttr('style')
    thhis.text('')
    for (var i = 0; i < amntOfChars; i++) {
      (function (i, char) {
        setTimeout(function () {
          newString += char
          thhis.text(newString)
        }, i * typingSpeed)
      })(i + 1, text[i])
    }
  }, 1500)
}

$(document).ready(function () {
  autoType('.type-js', 200)
})

export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  font-family: 'Anonymous Pro', monospace;
}
.text-js{
  opacity: 1;
}

@keyframes flash{
  0%{
    opacity: 1;
  }
  100%{
    opacity: 0;
  }
}

.cursor{
  display: block;
  position: absolute;
  height: 100%;
  top: 0;
  right: -5px;
  width: 2px;
  /* Change colour of Cursor Here */
  background-color: black;
  z-index: 1;
  animation: flash 0.2s none infinite alternate;
}

.headline{
  color: black;
  font-size: 32px;
  text-align: center;
  font-family: 'Anonymous Pro', monospace;
  h1{
    letter-spacing: 1.6px;
    font-weight: 300;
  }
}

</style>
