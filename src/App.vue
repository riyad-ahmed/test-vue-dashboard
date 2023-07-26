<script>
import sidebar from "./components/sidebar.vue";
import Header from "./components/Header.vue";
export default {
  components: {
    sidebar,
    Header,
  },
};
</script>

<template>
  <div id="app">
    <Header />
    <sidebar /> 
  </div>
</template>
