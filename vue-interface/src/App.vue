<template>
  <div id="main-app" class="container">
    <h4>{{title}}</h4>
  </div>
</template>

<script>
export default {
  name: "MainApp",
  data: function() {
    return {
      title: "Apoint List"
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
