<template>
  <div id="olien.Jumbotron">
    <b-jumbotron class="d-flex align-items-center justify-content-center text-center text-light rounded-0 m-0" :style="{'background': 'url(' + require('@/assets/home.jpg') + ') center center / cover no-repeat'}">
      <b-row class="m-0">
        <b-col sm="12">
          <h1 class="display-2 m-0">
            Oliën
          </h1>
        </b-col>
      </b-row>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'OlienJumbotron'
}
</script>

<style>
.jumbotron {
  font-family: papyrus;
  word-break: break-word;
  height: 40vh;
}
.jumbotron {
  font-family: papyrus;
  word-break: break-word;
}
</style>
