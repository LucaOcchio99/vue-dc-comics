<template>
   <section>
    <div class="container">
       <div class="icona">
          <img src="../assets/buy-comics-digital-comics.png" alt="">
           <span>DIGITAL COMICS</span>
       </div>

       <div class="icona">
          <img src="../assets/buy-comics-merchandise.png" alt="">
           <span>DC MERCHANDISE</span>
       </div>
       
       <div class="icona">
          <img src="../assets/buy-comics-subscriptions.png" alt="">
           <span>SUBSCRIPTION</span>
       </div>

       <div class="icona">
          <img src="../assets/buy-comics-shop-locator.png" alt="">
           <span>COMIC SHOP LOCATOR</span>
       </div>

       <div class="icona">
          <img src="../assets/buy-dc-power-visa.svg" alt="">
           <span>DC POWER VISA</span>
       </div>
    </div>      
   </section>
</template>

<script>
export default {
   name: 'Icone'
}
</script>

<style scoped lang="scss">
   .icona {
      display: flex;
      align-items: center;
      padding: 20px;
      img {
          height: 50px;
      }
      span {
        font-size: 12px;
        padding-left: 10px ;
      }
   }
   
   section {
       background-color: lightblue;
       display: flex;
   }

   .container {
       display: flex;
   }
</style>