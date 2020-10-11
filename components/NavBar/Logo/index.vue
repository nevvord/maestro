<template lang="pug">
nuxt-link(to="/").logo
  .logo__tonny Tonny
  .logo__mass Mass
</template>
<script>
export default {
  name: 'logo'
}
</script>
<style lang="scss" scoped>
.logo {
  display: flex;
  align-items: center;
  padding: 8px;
  text-decoration: none;
  &__tonny {
    font-size: 18px;
    font-weight: 600;
  }
  &__mass {
    color: darken(get-color(secondary, dark), 20);
    font-weight: 500;
  }
}
</style>
