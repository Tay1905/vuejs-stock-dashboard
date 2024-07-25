<template>
  <div id="app">
    <BaseCard>
      <h1>hello WSworld</h1>
    </BaseCard>
  </div>
</template>

<script>
import BaseCard from './components/BaseCard.vue';





export default {
  name: 'App',
  components: {
    BaseCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;

}

body {
  margin: 0;
  padding: 150px;
  background: radial-gradient(71.1% 100% at 50% 0%, #020204, #011F35 100%);
box-sizing: border-box;
height: 100vh;
width: 100vw;
}
</style>
