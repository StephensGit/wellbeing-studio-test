<template>
    <Header />
    <Events />
    <Learning />
    <Guides />
    <Footer />
</template>

<script>
import Header from '@/components/Header.vue'
import Events from '@/components/Events.vue'
import Learning from '@/components/Learning.vue'
import Guides from '@/components/Guides.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
    Header,
    Events,
    Learning,
    Guides,
    Footer
  }
}
</script>
