<template>
  <div id="Olien">
    <navbar />
    <jumbotron />
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/olien'
export default {
  name: 'Olien',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>

</style>
