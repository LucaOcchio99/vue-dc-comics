<template>
  <h1 class="testo">{{ text }}</h1>
</template>

<script>
export default {
  name: 'MainTitle',
  props: {
      text: String,
  }
}
</script>

<style scoped lang="scss">
.testo {
color: lightblue;
}
</style>