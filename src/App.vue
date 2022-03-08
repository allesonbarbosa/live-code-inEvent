<template>
  <Header />
  <FeatureList />
  <Footer />
</template>

<script>
import './styles/global.css'
import Header from './components/Header.vue'
import FeatureList from './components/FeatureList.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components:{
    Header,
    FeatureList,
    Footer
  }
}
</script>

<style scoped>

</style>