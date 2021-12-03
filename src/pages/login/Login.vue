<template>
  <div>
    <login-header></login-header>
    <login-section></login-section>
    <login-footer></login-footer>
  </div>
</template>

<script>
import LoginHeader from './components/Header'
import LoginSection from './components/Section'
import LoginFooter from './components/Footer'

export default {
  name: 'Login',
  components: {
    LoginHeader,
    LoginSection,
    LoginFooter
  }
}
</script>

<style>
</style>
