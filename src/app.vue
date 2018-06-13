<template>
    <div id="app">
      <div id="cover"></div>
      <Header></Header>
      <Footer></Footer>
    </div>
</template>

<script>
import Header from './todo/header.vue'
import Footer from './todo/footer.jsx'

export default {
  components: {
    Header,
    Footer
  }
};
</script>
<style>
#test {
  color: red;
}
</style>
