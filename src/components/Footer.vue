<template>
<section>
    <div class="container">
        <div class="left">
           <button>SIGN-UP NOW!</button>
        </div>

        <div class="right">
            <ul>
                <li><a href="">FOLLOW US</a></li>
                
                <li><a href=""><img src="../assets/footer-facebook.png" alt=""></a></li>
                 <li><a href=""><img src="../assets/footer-periscope.png" alt=""></a></li>
                  <li><a href=""><img src="../assets/footer-pinterest.png" alt=""></a></li>
                   <li><a href=""><img src="../assets/footer-twitter.png" alt=""></a></li>
                    <li><a href=""><img src="../assets/footer-youtube.png" alt=""></a></li>
            </ul>
        </div>
    </div>
</section>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped lang="scss">
section {
    background: lightgrey;
}
    .container {
        display: flex;

        .right,
        .left {
            width: 50%;
            padding: 2rem;
        }     
        
        .right {
            ul {
                display: flex;
                align-items: center;
                list-style: none;

                li {
                    padding: 5px;
                }
                 }
        }

        .left {
            display: flex;
            justify-content: flex-start;
            align-items: center;
        }
    }
</style>