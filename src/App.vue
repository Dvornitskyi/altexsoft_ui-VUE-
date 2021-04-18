<template>
  <div id="app">
    <TheHeader />
    <TheShout />
    <TheSlider />
    <TheContent />
    <TheFooter />
    <TheCopyright />
  </div>
</template>

<script>
import TheContent from './components/TheContent.vue'
import TheCopyright from './components/TheCopyright.vue'
import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheShout from './components/TheShout.vue'
import TheSlider from './components/TheSlider.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheSlider,
    TheContent,
    TheShout,
    TheFooter,
    TheCopyright,

  }
}
</script>

<style lang="scss">
*,
*:after,
*:before {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body,
input,
button,
textarea,
select {
  // font-family: sans-serif;
}

ul {
  list-style: none;
}

a,
button {
  background-color: transparent;
  border: none;
  outline: none;
  display: inline-flex;
  text-decoration: none;
}

textarea:hover,
a:hover,
input:hover {
  color: purple;
  transition: 1s;
}
textarea:active,
a:active,
input:active {
  color: yellow;
  transition: 1s;
}
input:active,
:hover,
:focus {
  outline: 0;
  outline-offset: 0;
}
</style>
