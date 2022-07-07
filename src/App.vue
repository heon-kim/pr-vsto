<template>
  <div id="app">
    <Homepage title="SHEILDInfo" />
    <Homepage msg="등급이 지정되지 않았습니다." />
    <img alt="mainImg" src="./assets/logo.png" />
    <img alt="SHEILDInfo logo" src="./assets/logo.png" />
  </div>
</template>

<script>
import Homepage from "./components/Homepage.vue";
// import selectLabel from "./components/selectLabel.vue";
// import selectGrade from "./components/seletGrade.vue";

export default {
  name: "App",
  components: {
    Homepage,
    // selectLabel,
    // selectGrade,
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
