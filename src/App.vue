<template>
  <div id="app">
    <ToDo />
  </div>
</template>

<script>
import ToDo from "./components/ToDo.vue";
export default {
  name: "app",
  components: {
    ToDo
  }
};
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, Helvetica,
    Arial, sans-serif;
  height: auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgb(131,58,180);
  background: linear-gradient(90deg, rgba(131,58,180,1) 0%, rgba(253,29,29,1) 50%, rgba(252,176,69,1) 100%);
}
input {
  width: 90%;
  font-size: 1em;
  margin: 10px 10px 10px auto;
  border-radius: 4px;
  padding: 12px;
  border-color: rgba(0, 0, 0, 0.1);
  background: #ffffff;
  box-shadow: 5px 5px 13px #d9d9d9, -5px -5px 13px #ffffff;
}
</style>
