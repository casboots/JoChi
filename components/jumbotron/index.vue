<template>
  <div id="index.jumbotron">
    <b-jumbotron class="d-flex align-items-center justify-content-center text-center text-light rounded-0 m-0" :style="{'background': 'url(' + require('@/assets/home.jpg') + ') center center / cover no-repeat'}">
      <b-row class="m-0">
        <b-col sm="12">
          <h1 class="display-1 m-0">
            JoChi
          </h1>
          <h3 class="h3 m-0">
            VoetreflexPlus Therapie & Do-In Yoga
          </h3>
          <p class="h5 m-0">
            In Balans door Innerlijke Kracht
          </p>
        </b-col>
      </b-row>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'index.jumbotron'
}
</script>

<style>
.jumbotron {
  font-family: papyrus;
  word-break: break-word;
  height: 40vh;
}
</style>
