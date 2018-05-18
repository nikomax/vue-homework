<template>
  <div id="app">
    <custom-header/>
    <router-view/>
    <custom-footer/>
  </div>
</template>

<script>
import CustomHeader from '@/components/CustomHeader'
import CustomFooter from '@/components/CustomFooter'
export default {
  name: 'App',
  components: {
    CustomHeader, CustomFooter
  }
}
</script>

<style lang="sass">
@import sass/app

</style>
