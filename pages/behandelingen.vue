<template>
  <div id="Behandelingen">
    <navbar />
    <jumbotron />
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/behandelingen'
export default {
  name: 'Behandelingen',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>

</style>
