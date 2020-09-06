<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <AppFooter />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import AppFooter from '@/components/AppFooter'
  export default {
    components: {
      Navbar,
      AppFooter
    }
  }
</script>

<style>

</style>
