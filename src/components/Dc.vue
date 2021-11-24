<template>
  <section>
     <div class="container">
         <div class="left">
         <!-- col left -->
         <div>
            <h4>DC COMICS</h4>
            <nav>
                <ul>
                    <li><a href="">Characters</a></li>
                     <li><a href="">Comics</a></li>
                      <li><a href="">Movies</a></li>
                       <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                         <li><a href="">Videos</a></li>
                          <li><a href="">News</a></li>
                </ul>
            </nav>
            
            <h4>SHOP</h4>
            <nav>
                <ul>
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
                </ul>
            </nav>
         </div>


         <!-- col center -->
         <div>
             <h4>DC COMICS</h4>
            <nav>
                <ul>
                    <li><a href="">Characters</a></li>
                     <li><a href="">Comics</a></li>
                      <li><a href="">Movies</a></li>
                       <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                         <li><a href="">Videos</a></li>
                          <li><a href="">News</a></li>
                </ul>
            </nav>
         </div>
         <!-- col right -->
         <div class="mg-left">
            <h4>SITIES</h4>
            <nav>
                <ul>
                    <li><a href="">DC</a></li>
                     <li><a href="">MAD Magazine</a></li>
                      <li><a href="">DC Kids</a></li>
                       <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                </ul>
            </nav>
         </div>
     </div>

     <div class="right">
         <img src="../assets/dc-logo-bg.png" alt="">
     </div>
     </div>
  </section>
</template>

<script>
export default {
  name: 'Dc'
}
</script>

<style scoped lang="scss">

 section {
     background-image: url(../assets/footer-bg.jpg);
     background-size: 100%;
}

.container {
    display: flex;
    height: 286px;
    
    .left {
        width: 50%;
        display: flex;
        padding: 2rem;
    }

    .right {
        width: 50%;
        display: flex;
        justify-content: center
     
     img {
         height: 50%;
     }
    }
}

ul {
    list-style: none;
    a {
        text-decoration: none;
        color: grey;
    }
}

.mg-left {
     margin-left: 30px;
 }

 h4 {
     margin-bottom : 1rem;
     color: white;
 }

</style>