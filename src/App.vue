<template>
  <div id="app">
    <div class="video-wrap">
      <video class="video" controls loop>
        <source src="./assets/8k.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
</template>
<script>

export default {
  name: 'App',
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}
.video {
  width: 100%;
  height: 100%;
}
.video-wrap {
  width: 100%;
  height: 100%;
}
</style>
