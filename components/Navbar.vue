<template>
  <div id="Navbar">
    <b-navbar toggleable="lg" type="dark" variant="primary" class="text-center">
      <nuxt-link to="/">
        <img :src="require('@/assets/logo.png')" :width="40" :height="40" alt="logo" class="mr-2">
      </nuxt-link>
      <nuxt-link to="/" class="navbar-brand">
        JoChi
      </nuxt-link>
      <b-navbar-toggle target="Nav-Collapse" />
      <b-collapse id="Nav-Collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item>
            <nuxt-link to="/" class="nav-link">
              Home
            </nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/behandelingen" class="nav-link">
              Behandelingen
            </nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/groepslessen" class="nav-link">
              Groepslessen
            </nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/olien" class="nav-link">
              Oliën
            </nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/about" class="nav-link">
              About
            </nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/contact" class="nav-link">
              Contact
            </nuxt-link>
          </b-nav-item>
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
