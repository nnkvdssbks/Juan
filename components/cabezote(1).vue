<template>
    <div>
      <v-app-bar 
        image="https://bisuteriafina.com.mx/wp-content/uploads/bfi_thumb/BANNER-326wqm1fuvl9fv02l4yvtw19aj2b73dcu7tomfuzhfycxjx74.jpg"
        dark
        height="150"
      >
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
  
        <v-toolbar-title  
        ><h1>BISUTERIA MARY</h1></v-toolbar-title>
  
        <v-spacer></v-spacer>
  
        <carrito class="mr-5"
         :productos="productos"
        >

        </carrito>
      </v-app-bar>
      
    </div>
  </template>
  <script>
  export default {
    props:{
      productos : Array,
    }
  }
  </script>
  <style scoped>
   
  </style>