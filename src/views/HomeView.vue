<template>
  <div class="home">
    <HeroSection></HeroSection>
  </div>
</template>

<script>
// @ is an alias to /src
import HeroSection from '@/components/HomePage/HeroSection.vue'

export default {
  name: 'HomeView',
  components: {
    HeroSection,
}
}
</script>
