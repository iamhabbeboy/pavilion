<template>
  <div id="app">
    <Header />
    <MinHeader />
    <Content />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import MinHeader from './components/MinHeader.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'app',
  components: {
    Header,
    MinHeader,
    Content,
    Footer
  }
}
</script>

<style>
</style>
