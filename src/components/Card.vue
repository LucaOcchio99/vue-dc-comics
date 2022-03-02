<template>
  <div>
      <!-- Quindi le props servono proprio a questo... product chi è? non è presente qui. Servono che esso venga passato -->
        <img :src="url" :alt="title">
                  <h3>{{ title }}</h3>
  </div>
</template>

<script>
export default {
 name: 'Card',
 props: {
     url: String,
     title: String, //Number Boolen Object Array...

 }
}
</script>

<style scoped lang="scss">
.card {
    height: 100%;
    padding-bottom: 1rem;
    background: #fff;
}
</style>