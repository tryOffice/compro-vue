<script>
import feather from 'feather-icons'
import AboutMe from '@/components/about/AboutMe.vue'
// import AboutCounter from '@/components/about/AboutCounter.vue'
import AboutClients from '@/components/about/AboutClients.vue'

export default {
  name: 'About',
  components: {
    AboutMe,
    // AboutCounter,
    AboutClients
  },
  data: () => {
    return {}
  },
  mounted() {
    feather.replace()
  },
  updated() {
    feather.replace()
  },
  methods: {}
}
</script>

<template>
  <div>
    <!-- About me -->
    <div class="container mx-auto">
      <AboutMe />
    </div>

    <!-- About counter -->
    <!-- <AboutCounter /> -->

    <!-- About counter -->
    <div class="container mx-auto">
      <AboutClients />
    </div>
  </div>
</template>

<style scoped></style>
