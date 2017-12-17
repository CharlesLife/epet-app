<template>
  <div>
    <epet-header></epet-header>
    <epet-main></epet-main>
    <epet-footer></epet-footer>
  </div>
</template>

<script>
  import header from './components/header/header.vue'
  import main from './components/main/main.vue'
  import footer from './components/footer/footer.vue'
  export default {
  components: {
    'epet-header': header,
    'epet-main': main,
    'epet-footer': footer
  }
}
</script>

<style>

</style>
