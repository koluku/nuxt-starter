<template lang="pug">
  .NuxtLogo.lazyload
</template>

<style lang="scss" scoped>
.NuxtLogo {
  @include image('logo', 245px, 180px);

  animation: 1s appear;
  margin: auto;
}
</style>
