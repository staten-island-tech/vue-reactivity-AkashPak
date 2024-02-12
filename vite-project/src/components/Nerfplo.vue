<template>
  <div> 
    <DestCard
    v-for="destination in destinations" 
    :key="destination.name"
    :Destination="destination"
  />
 </div>
</template>

<script setup>
const pusheenthecatthriftshop= [
  {
    name: "MerPusheen",
    price: 1300,
    img: "https://m.media-amazon.com/images/I/71LfBMvMLQL.__AC_SX300_SY300_QL70_FMwebp_.jpg"
  }, 
  {
    name:"CinnPusheen",
    price: 800,
    img:"https://i.pinimg.com/736x/97/56/f0/9756f009fc508b7650bdfdca4f1675b6.jpg",
  },
  {
    name:"SmorPusheen",
    price: 800,
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/Pusheen_S_mores_Squisheen_021_web_1000x1000.jpg?v=1673384811",
  },
  {
    name:"",
    price: 800,
    img:"https://images-na.ssl-images-amazon.com/images/I/41kAh0oGxvL._SL500_AC_SS350_.jpg",
  },
  {
    name:"Modulus Scope",
    price: 800,
    img:"https://images-na.ssl-images-amazon.com/images/I/41kAh0oGxvL._SL500_AC_SS350_.jpg",
  },
  {
    name:"Modulus Scope",
    price: 800,
    img:"https://images-na.ssl-images-amazon.com/images/I/41kAh0oGxvL._SL500_AC_SS350_.jpg",
  }



]




</script>