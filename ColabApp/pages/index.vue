<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        {{ $t('home.title') }} 
      </h1>
      <h2 class="subtitle">
        {{ $t('home.introduction') }} 
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
  import Index from '~/pages/_lang/index'
  export default Index
</script>

<style>
</style>
