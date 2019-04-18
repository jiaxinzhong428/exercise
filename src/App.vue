<template>
  <div id="app">
    <img src="./assets/logo.png" alt="">
    <h1>{{msg}}</h1>
    <firstcomponent></firstcomponent>
    <secondcomponent></secondcomponent>
  </div>
</template>
<script>
import firstcomponent from "./component/firstcomponent.vue";
import secondcomponent from "./component/secondcomponent.vue";
export default {
  data() {
    return {
      msg: "hello vue!"
    };
  },
  components: {
    firstcomponent,
    secondcomponent
  }
};
</script>
<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>


