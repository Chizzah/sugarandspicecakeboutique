<template>
  <Layout>
    <section class="relative h-110 flex flex-col justify-center items-center sm:h-128 sm:text-lg">
      <div class="w-92 py-8 px-6 bg-pink-400 text-gray-200 rounded sm:w-128">
        <h1 class="pb-2 text-xl font-semibold text-center text-gray-900 sm:text-xl">Your message has been sent succesfully!</h1>
        <p class="pb-2 text-center">Thank you for contacting me. I will get back to you as soon as possible.</p>
        <p class="text-gray-900 text-center text-xxs font-semibold"><g-link to="/">Click here to go back to home</g-link></p>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Success'
  }
}
</script>