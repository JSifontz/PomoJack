<template>
  <div id="app">
    <span class="message">{{ msg }}</span>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to the PomoJack begin'
    }
  }
}
</script>

<style>
  .message {
    color: peru;
    font-size: 5vw
  }

  #app {
    height: 97vh;
    width: 99vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
