<template>
  <div id="Groepslessen">
    <navbar />
    <jumbotron />
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/groepslessen'
export default {
  name: 'Groepslessen',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>

</style>
