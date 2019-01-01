<template>
  <div id="start">
    <div class="background"></div>
    <div id="logo"></div>
  </div>
</template>

<script>

  export default {
    name: 'App',
    components: {},
    data() {
      return {}
    }
  }
</script>

<style scoped>

  .background {
    background: black url(./assets/background3.png) center;
    position: fixed;
    left: 0;
    top: 0;
    width: 100vw;
    height: 100vh;
    z-index: -1;
  }

  #logo {
    background: url(./assets/rise_in_time.png) no-repeat;
    background-size: contain;
    width: 613px;
    height: 124px;
    margin: 0 auto;
  }

  @media (max-width: 768px) {
    #logo {
      width: 300px;
      height: 61px;
    }
  }

</style>
