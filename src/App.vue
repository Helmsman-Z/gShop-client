<template>
  <div class="app">
    <router-view></router-view>
    <FooterGuide v-show="$route.meta.ShowFooter"/>
  </div>
</template>

<script>
import FooterGuide from './components/FooterGuide/FooterGuide'
export default {
  components: {
    FooterGuide
  }
}
</script>

<style>

</style>
