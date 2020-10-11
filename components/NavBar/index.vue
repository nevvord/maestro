<template lang="pug">
nav.navbar
  Logo
</template>
<script>
import Logo from './Logo'
export default {
  name: 'navigate-bar',
  components: {
    Logo
  }
}
</script>
<style lang="scss" scoped>
.navbar {
  background-color: get-color(primary, main);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  max-height: 43px;
}
</style>