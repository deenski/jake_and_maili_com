<template>
  <div class="bg">
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
  height: 100%;
}

body {
  height: 100%;
}

.bg {
  /* The image used */
  background-image: url("/bg.jpg");

  /* Full height */
  height: 100%;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
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

.card {
  border: 2px solid beige;
  border-radius: 25px;
  padding: 50px;
  margin: 0 auto;
  position: relative;
  max-width: 900px;
  background: rgba(55, 55, 55, 0.6);
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
  text-align: center;
}

h3 {
  font-weight: 260;
  font-size: 36px;
  color: #f9f3db;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align: left;
  text-decoration: underline;
}

.content {
  font-weight: 225;
  font-size: 32px;
  color: #f9f3db;
}

.links {
  color: #f0adb6;
  text-decoration: underline;
}

.links:hover {
  color: beige;
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

.code-container {
  margin: 0 auto;
  min-height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

pre {
  width: 40%;
  height: auto;
  text-align: left;
  background-color: #000;
}
pre code {
  background-color: #000;
  color: #fff;
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .title {
    font-size: 125%;
  }

  .subtitle {
    font-size: 125%;
  }

  h3 {
    font-size: 125%;
  }

  .content{
    font-size: 125%;
  }

}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .title {
    font-size: 125%;
  }

  .subtitle {
    font-size: 125%;
  }

  h3 {
    font-size: 125%;
  }

  .content{
    font-size: 125%;
  }

}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .title {
    font-size: 300%;
  }

  .subtitle {
    font-size: 225%;
  }

  h3 {
    font-size: 225%;
  }

  .content {
    font-size: 125%;
  }
}
</style>
