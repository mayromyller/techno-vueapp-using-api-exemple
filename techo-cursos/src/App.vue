<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
  </div>
</template>
<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header
  }
};
</script>
<style>
@import url("https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap");
body {
  margin: 0px;
  font-family: "Josefin Sans", sans-serif;
  color: #234;
}
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
a {
  font-weight: bold;
  text-decoration: none;
  color: #234;
}
a.router-link-active {
  color: #4b8;
}
</style>
