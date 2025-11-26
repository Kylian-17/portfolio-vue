<template>
  <div id="app">
    <Header />
    <Portfolio />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/header.vue";
import Portfolio from "./components/portfolio.vue";
import Footer from "./components/footer.vue";
import test from "./components/test.vue";

export default {
  components: {
    Portfolio,
    Header,
    Footer,
    test,
  },
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
</style>
