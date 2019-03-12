<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        netlify-proxy-2019
      </h1>
      <h2 class="subtitle">
        My marvelous Nuxt.js project
      </h2>

      <nuxt-link to="/2019/about/">
        about
      </nuxt-link>

      <nuxt-link to="/2018/">
        2018
      </nuxt-link>

      <div class="link-to-github">
        <a
          href="https://github.com/inouetakuya/netlify-proxy-2019"
          target="_blank"
        >
          <img src="~/assets/images/github.svg" />
        </a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
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
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.link-to-github {
  margin-top: 15px;
}
</style>
