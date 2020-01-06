<template>
  <div id="app">
    <div class="hh" w-188-246 aspectratio>
      <div aspectratio-content class="ss">

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}
#app {
  width: 100vw;
  height: 100vh;
  overflow-y: auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
img {
    content: normal !important;
}
[aspectratio] {
    position: relative;
}
[aspectratio]::before {
    content: '';
    display: block;
    width: 1px;
    margin-left: -1px;
    height: 0;
}

[aspectratio-content] {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
}
[w-188-246] {
    aspect-ratio: '188:246';
}
.hh{
  width: 375px;
  background: #2c3e50;
}
</style>
