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
    background: rgba(0, 0, 0, 0.856);
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
                   
                  a {
                      color: lightblue;
                      text-decoration: none;
                  }
                }
                 }
        }

        .left {
            display: flex;
            justify-content: flex-start;
            align-items: center;

            button {
                padding: 10px;
                color: white;
                background-color: rgba(66, 66, 228, 0.644);
                border-radius: 50px;
                border: none;
                cursor: pointer;
            }
        }
    }
</style>