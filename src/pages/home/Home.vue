<template>
  <div>
    <home-header></home-header>
    <home-section></home-section>
    <home-footer></home-footer>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSection from './components/Section'
import HomeFooter from './components/Footer'

export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSection,
    HomeFooter
  }
}
</script>

<style>

</style>
