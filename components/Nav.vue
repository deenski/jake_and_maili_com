<template>
  <div class="nav-container">
    <div class="links">
      <router-link to="/" target="self" class="button--green">
        Home
      </router-link>
      <router-link to="/events" target="self" class="button--green">
        Events
      </router-link>
      <router-link to="/accomodations" target="self" class="button--green">
        Accomodations
      </router-link>
      <router-link to="/details" target="self" class="button--green">
        Details
      </router-link>
      <router-link to="/photos" target="self" class="button--green">
        Photos
      </router-link>
      <router-link to="/gifts" target="self" class="button--green">
        Gifts
      </router-link>
      <router-link to="/contact" target="self" class="button--green">
        RSVP
      </router-link>
    </div>
  </div>
</template>

<style>
.nav-container {
  margin: 0 auto;
  min-height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.links {
  padding-top: 15px;
  padding-right: 15px;
}
</style>
