<template>
  <div id="Index">
    <navbar />
    <jumbotron />
    <div class="m-0">
      <div class="bg-primary">
        <b-container fluid class="bg-primary">
          <b-card no-body class="overflow-hidden mt-3 mb-3 rounded-0 no-border bg-primary">
            <b-row no-gutters>
              <b-col xl="3">
                <b-img-lazy :src="require('@/assets/profile.jpg')" class="rounded-circle square mt-3 mb-3" />
              </b-col>
              <b-col xl="9">
                <b-card-body>
                  <b-card-text>
                    <p class="h6">
                      Bij Do-In Yoga kom je tot rust, je ademhaling gaat langzamer en je wordt je bewuster van allerlei interessante dingen. Kortom een “Weg naar binnen” een Bijzondere Weg! Kom zelf ervaren wat Do-In Yoga voor jou kan betekenen.
                    </p>
                  </b-card-text>
                </b-card-body>
              </b-col>
            </b-row>
          </b-card>
        </b-container>
      </div>

      <b-container>
        <b-card no-body class="overflow-hidden mb-3 rounded-0 no-border">
          <b-row no-gutters>
            <b-col xl="4" class="text-center">
              <b-card-img-lazy :src="require('@/assets/do-in.jpg')" class="rounded-0" />
            </b-col>
            <b-col xl="8">
              <b-card-body>
                <b-card-text>
                  <nuxt-link to="/do-in" class="h1 text-dark papyrus-title">
                    Do-In Yoga
                  </nuxt-link>
                  <p>
                    Bij Do-In Yoga kom je tot rust, je ademhaling gaat langzamer en je wordt je bewuster van allerlei interessante dingen. Kortom een “Weg naar binnen” een Bijzondere Weg! Kom zelf ervaren wat Do-In Yoga voor jou kan betekenen.
                  </p>
                </b-card-text>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </b-container>
    </div>
    <page-footer />
  </div>
</template>

<script>
import navbar from '@/components/Navbar'
import pageFooter from '@/components/Footer'
import jumbotron from '@/components/jumbotron/index'
export default {
  name: 'Index',
  components: {
    navbar,
    pageFooter,
    jumbotron
  }
}
</script>

<style>
.no-border {
  border: none;
}
.square {
  height: 300px;
  width: 300px;
}
.papyrus-title {
  font-family: papyrus;
}
</style>
