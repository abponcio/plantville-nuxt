<template>
  <div>
    <MiniHeader/>
    <Nav/>
    <section>
      <nuxt />
    </section>
    <Footer/>
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import MiniHeader from '~/components/MiniHeader.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Nav,
    MiniHeader,
    Footer,
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 12px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>