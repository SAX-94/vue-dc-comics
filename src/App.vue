<template>
  <div id="app">
    <TheNavbar></TheNavbar>
    <MainContent></MainContent>
    <TheFooter></TheFooter>
    <SignUp></SignUp>
  </div>
</template>

<script>
import TheNavbar from './components/TheNavbar.vue'
import MainContent from './components/MainContent.vue'
import TheFooter from './components/TheFooter.vue'
import SignUp from './components/SignUp.vue'

export default {
  name: 'App',
  components: {
    TheNavbar,
    MainContent,
    SignUp,
    TheFooter
  }
}
</script>

<style lang="scss">
</style>
