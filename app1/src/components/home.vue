<template>
<div>
    <Header />
    <h1> Hello Home Page test</h1>
    <Team />
    <Footer />
</div>
</template>
<script>
import Header from './header.vue'
import Footer from './footer.vue'
import Team from './team.vue'
export default {
  name: 'home',
  components: {
    Header,
    Footer,
    Team
  },
  data () {
    return {
    }
  }
}
</script>
<style>
</style>
