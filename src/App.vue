<template>
  <div id="app">
    <div class="card">
    <Fighter/>
    </div>
      <Main/>
    <div class="card">
      <Fighter/>
    </div>
  </div>
</template>

<script>

import Fighter from "./components/Fighter";
import Main from "./components/Main";

export default {
  name: 'App',
  components: {
    Fighter,
    Main

  }
}
</script>

<style>
#app {
  display: flex;
}
.card{
  height: 400px;
  width: 33.33%;
  background-color: aqua;
  margin: 0 auto;
}
</style>
