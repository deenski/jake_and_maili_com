<template>
  <div>
    <navigation />
    <nuxt />
  </div>
</template>

<script>
import Navigation from '~/components/Nav.vue'
export default {
  components: {
    Navigation
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background-image: url('https://source.unsplash.com/AsahNlC0VhQ/1920x1080');
  background-repeat: no-repeat;
  background-attachment: fixed;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.container {
  margin: 0 auto;
  min-height: 90vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 85px;
  color: #f9f3db;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #f9f3db;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.content {
  font-weight: 225;
  font-size: 32px;
  color: #f9f3db;
}

.links {
  color: #82947d;
}

.links:hover {
  color: #f9f3db;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #f9f3db;
  color: #f9f3db;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #000;
  background-color: #f9f3db;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
