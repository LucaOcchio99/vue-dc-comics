<template>
  <header class="container text-center">
    <div class="left">
     <a href="">
       <img src="../assets/dc-logo.png" alt="">
     </a>
</div>

<div class="right">
     <nav>
       <ul>
         <li v-for="(link,index) in navLink" :key="`link-${index}`">
           <a :class="{active: link.current}" 
           href="/">
           {{ link.text }}</a>
         </li>
       </ul>
     </nav>
     </div>
  </header>
</template>

<script>

export default {
   name: 'Header',
   data () {
     return {
       navLink: [
         {
           text: 'CHARACTERS',
           url: '/',
           current: true,
         },
         {
           text: 'COMICS',
           url: '/',
           current: false,
         },
         {
           text: 'MOVIES',
           url: '/',
           current: false,
         },
         {
           text: 'TV',
           url: '/',
           current: false,
         },
         {
           text: 'GAMES',
           url: '/',
           current: false,
         },
         {
           text: 'COLLECTIBLES',
           url: '/',
           current: false,
         },
         {
           text: 'VIDEOS',
           url: '/',
           current: false,
         },
         {
           text: 'FANS',
           url: '/',
           current: false,
         },
         {
           text: 'NEWS',
           url: '/',
           current: false,
         },
         {
           text: 'SHOP',
           url: '/',
           current: false,
         },
       ],
     }
   }
}
</script>

<style scoped lang="scss">
   header {
     display: flex;

     .left{
       width: 50%;
     }

     .right {
       width: 50%;
       display: flex;
       justify-content: center;
       align-items: center;
     }
   }
   ul {
     display: flex;
     list-style: none;
     justify-content: center;
     font-size: 12px;

     a {
       display: inline-block;
       padding: 6px;
       text-decoration: none;
       color: #000;
       &.active,
       &:hover {
         background-color: lightblue;
       }
     }
   }

</style>