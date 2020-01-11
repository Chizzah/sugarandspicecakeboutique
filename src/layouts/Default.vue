<template>
  <section>
    <Header />
    <slot/>
    <Footer />
  </section>
</template>

<script>
import Header from '~/components/Header.vue';
import Footer from '~/components/Footer.vue';
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html {
  font-family: 'Nunito', sans-serif;
  font-weight: 400;
}

h1,
h2 {
  font-family: 'Halant', serif;
  font-weight: 400
}
</style>
