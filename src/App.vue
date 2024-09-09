<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <app-header />
</template>

<script>
export default {
  name: "App",
  components: {
    AppHeader: "<button>btn</button>",
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
