<template>
  <Tutorial/>
</template>

<script>
export default {
  name: 'Home',

  mounted () {
    var root = document.getElementsByTagName( 'html' )[0]

    if (false) {
      root.classList.add('partner-1')
    } else {
      root.classList.add('default')
    }
  }
}
</script>

<style lang="scss">
@import '@/assets/stylesheet/styleguide.scss'
</style>
