<template>
  <layout>
    <section class="flex flex-col justify-center items-center text-center">
      <h1 class="mt-12 mx-8 text-pink-500 text-center font-semibold uppercase md:text-4xl md:mx-128 md:mb-20">Let us know what cake you want and when you need it!</h1> 
      <p class="mx-4 mt-4 mb-8">We'll contact you to setup a meeting to ensure your cake is everything you want it to be.</p>
      <Form />
    </section>
  </layout>
</template>

<script>
import Form from '~/components/Form.vue';

export default {
  components: {
    Form
  }
}
</script>