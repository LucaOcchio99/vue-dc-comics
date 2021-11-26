<template>
   <section class="text-center">
       <div class="immagine">
           <img src="../assets/jumbotron.jpg" alt="">
       </div>
      
      <div class="container">
        <!-- <h1>CURRENT SERIES</h1> -->
        <MainTitle text="CURRENT SERIES" />
          
          <ul class="boxes">
              <li v-for="(product, index) in products" :key="`prod-${index}`">
                <!--  <img :src="product.thumb" :alt="product.series">
                  <h3>{{ product.series }}</h3> --> 

                  <Card :url="product.thumb" :title="product.series"/>
              </li>
          </ul>
            <button> LOAD MORE </button>
      </div>
   </section>
</template>

<script>
import Card from '@/components/Card.vue'
import MainTitle from '@/components/MainTitle.vue';
import  ProdSeries from '@/data/dc-comics.js'

export default {
  name: 'Hero',
  components: {
    Card,
    MainTitle
  },
  data() {
      return {
         products : ProdSeries, 
      }
  }
}
</script>

<style scoped lang = 'scss' >
 img {
     height: 250px;
     width: 100%;
 }

section {
    background: rgba(0, 0, 0, 0.856);
}

.boxes {
    display: flex;
    flex-wrap: wrap;
    list-style: none;

    li {
        width: calc(100% / 6);
        padding: 6px;
        color: white;
        
    }
}

button {
    padding: 10px;
    background: rgba(0, 0, 255, 0.644);
    color: white;
    margin-bottom: 2rem;
    border: none;
    cursor: pointer;
}
</style>