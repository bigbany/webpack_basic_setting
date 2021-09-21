<template>
  <li>{{ name }}5!</li>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: ''
    }
  }
}

</script>


<style scoped lang="scss">
h1 {
  color: red !important;
}
</style>