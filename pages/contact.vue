<template>
  <div id="Contact">
    <navbar />
    <jumbotron />
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/contact'
export default {
  name: 'Contact',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>

</style>
