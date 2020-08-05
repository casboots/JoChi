<template>
  <div id="pageFooter" class="container-fluid bg-primary text-light mt-3">
    <b-row class="text-center p-2">
      <b-col md="4" class="mt-1 mb-3">
        <h1 class="h1 mb-3">
          Contact
        </h1>
        <p class="h5 mb-3">
          Jolanda Pistor
        </p>
        <p class="h5 mb-3">
          <a href="mailto:info@jochi.nl?SUBJECT=" class="text-light">
            <i class="fas fa-envelope" /> info@jochi.nl
          </a>
        </p>
        <p class="h5 mb-3">
          <a href="tel:+31644083612" class="text-light">
            <i class="fas fa-phone" style="transform:rotate(90deg)" /> 06 4408
            3612
          </a>
        </p>
      </b-col>
      <b-col md="4" class="mt-1 mb-3" @click="sendTo('maps')">
        <h1 class="h1 mb-3">
          Adres
        </h1>
        <p class="h5 mb-3">
          Dreef
        </p>
        <p class="h5 mb-3">
          Dreef 6
        </p>
        <p class="h5 mb-3">
          1701 GP, Heerhugowaard
        </p>
      </b-col>
      <b-col md="4" class="mt-1 mb-3">
        <h1 class="h1 mb-3">
          Blijf op de hoogte
        </h1>
        <b-row class="mb-2" @click="sendTo('laposta')">
          <b-col md="1" />
          <b-col md="10">
            <b-container>
              <b-input-group inline>
                <b-form-input placeholder="email@adress.nl" />
                <template v-slot:append>
                  <b-button variant="outline-light">
                    Inschrijven
                  </b-button>
                </template>
              </b-input-group>
            </b-container>
          </b-col>
          <b-col md="1" />
        </b-row>
        <b-row>
          <b-col md="4" />
          <b-col md="4">
            <i class="fab fa-facebook h1 m-1" @click="sendTo('facebook')" />
            <i class="fab fa-linkedin h1 m-1" @click="sendTo('linkedin')" />
          </b-col>
          <b-col md="4" />
        </b-row>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'PageFooter',
  data () {
    return {
      urls: {
        maps: 'https://goo.gl/maps/Eeq4Tr3bBYjHHJVG8',
        facebook: 'https://www.facebook.com/Jochi.shiatsutherapeut?ref=hl',
        linkedin: 'https://www.linkedin.com/in/jolanda-pistor-67430a60',
        laposta: 'https://laposta.nl/f/ssxsllr4q1zy',
        jochi: 'https://jochi.nl'
      }
    }
  },
  methods: {
    sendTo (site) {
      let link = ''
      if (site === 'maps') {
        link = this.urls.maps
      } else if (site === 'facebook') {
        link = this.urls.facebook
      } else if (site === 'linkedin') {
        link = this.urls.linkedin
      } else if (site === 'laposta') {
        link = this.urls.laposta
      } else {
        link = this.urls.jochi
      }
      window.open(link)
    }
  }
}
</script>

<style scoped>
.container-fluid {
  font-family: papyrus;
}
</style>
