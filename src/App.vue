<template>
  <div id="app">
    <TheNavbar></TheNavbar>
    <MainContent></MainContent>
    <BlueBanner></BlueBanner>
    <TheFooter></TheFooter>
    <SignUp></SignUp>
  </div>
</template>

<script>
import TheNavbar from './components/TheNavbar.vue'
import MainContent from './components/MainContent.vue'
import TheFooter from './components/TheFooter.vue'
import SignUp from './components/SignUp.vue'
import BlueBanner from './components/BlueBanner.vue'

export default {
  name: 'App',
  components: {
    TheNavbar,
    MainContent,
    SignUp,
    TheFooter,
    BlueBanner
}
}
</script>

<style lang="scss">
</style>
