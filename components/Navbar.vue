<template>
  <div id="Navbar">
    <b-navbar toggleable="lg" type="dark" variant="primary" class="text-center">
      <img :src="require('@/assets/logo.png')" :width="38" :height="38" alt="logo" class="mr-2">
      <nuxt-link to="/" class="navbar-brand">
        JoChi
      </nuxt-link>
      <b-navbar-toggle target="Nav-Collapse" />
      <b-collapse id="Nav-Collapse" is-nav>
        <b-navbar-nav>
          <b-navbar-item>
            <nuxt-link to="/" class="nav-link">
              Home
            </nuxt-link>
          </b-navbar-item>
          <b-navbar-item>
            <nuxt-link to="/behandelingen" class="nav-link">
              Behandelingen
            </nuxt-link>
          </b-navbar-item>
          <b-navbar-item>
            <nuxt-link to="/groepslessen" class="nav-link">
              Groepslessen
            </nuxt-link>
          </b-navbar-item>
          <b-navbar-item>
            <nuxt-link to="/olien" class="nav-link">
              Oliën
            </nuxt-link>
          </b-navbar-item>
          <b-navbar-item>
            <nuxt-link to="/about" class="nav-link">
              About
            </nuxt-link>
          </b-navbar-item>
          <b-navbar-item>
            <nuxt-link to="/contact" class="nav-link">
              Contact
            </nuxt-link>
          </b-navbar-item>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto" />
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
nav {
  font-family: papyrus;
}
</style>
