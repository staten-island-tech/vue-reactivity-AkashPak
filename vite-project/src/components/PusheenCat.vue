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
    Type: "Water",
    img: "https://m.media-amazon.com/images/I/71LfBMvMLQL.__AC_SX300_SY300_QL70_FMwebp_.jpg"
  }, 
  {
    name:"CinnPusheen",
    Type: 'Food',
    img:"https://i.pinimg.com/736x/97/56/f0/9756f009fc508b7650bdfdca4f1675b6.jpg",
  },
  {
    name:"SmorPusheen",
    Type: 'Food',
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/Pusheen_S_mores_Squisheen_021_web_1000x1000.jpg?v=1673384811",
  },
  {
    name:"RainbowPusheen",
    Type: "Normal",
    img:"https://i.pinimg.com/736x/36/b4/ac/36b4ac0154207a8f976f5cbf00f473c9.jpg",
  },
  {
    name:"CookiePusheen",
    Type: "Normal",
    img:"https://www.teslastoys.com/wp-content/uploads/2017/03/PUS-PT001-800x800.jpg",
  },
  {
    name:"SlothAndCat",
    Type: "Tog",
    img:"https://i.pinimg.com/originals/44/94/b1/4494b1456a0fb26f54d6df7338cc1bf9.png",
  },
  {
    name:"MiniNem",
    Type: "Tog",
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/group_classic_plush_004_700x700.png?v=1551139427",
  },  
  {
    name:"F&F",
    Type: "Tog",
    img:"https://pbs.twimg.com/media/Fx84z17XoAAWjtc.jpg",
  },  
  {
    name:"CandyPusheen",
    Type: "Normal",
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/candy-cane-plush-1_760x.png?v=1541111705%27",
  },  
  {
    name:"BdayColorPusheen",
    Type: "Normal",
    img:"https://i.pinimg.com/736x/5a/4f/18/5a4f181aa0396d2e44b20ee1f3364bc1.jpg",
  },
  


]




</script>