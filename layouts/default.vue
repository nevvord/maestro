<template lang="pug">
.default
  NavigateBar.default__navigate-bar
  nuxt.default__content
  Footer.default__footer
</template>

<script>
import NavigateBar from '~/components/NavBar'
import Footer from '~/components/Footer'
export default {
  name: 'default',
  components: {
    NavigateBar,
    Footer
  }
}
</script>

<style lang="scss" scoped>
.default {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  padding-top: 43px;
  &__navigate-bar {}
  &__content {}
  &__footer {
    margin-top: auto;
  }
}
</style>
