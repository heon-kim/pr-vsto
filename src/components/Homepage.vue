f
<template>
  <div>
    <div class="title">
      {{ title }}
    </div>
    <div class="main">
      <p>{{ msg }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  props: {
    title: String,
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title {
  background-color: #0167b8;
  color: white;
  text-align: left;
}
</style>
