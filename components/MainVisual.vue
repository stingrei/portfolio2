<template lang="pug">
.mv
  p.sp test
  h2 test3
</template>

<style lang="sass">
@import '~/assets/sass/_config.sass'
@import '~/assets/sass/_mixins.sass'
.mv
  p
    color: red
    +sp
      +tategaki()
</style>