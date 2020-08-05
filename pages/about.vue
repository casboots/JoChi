<template>
  <div id="About">
    <navbar />
    <jumbotron />
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/about'
export default {
  name: 'About',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>

</style>
