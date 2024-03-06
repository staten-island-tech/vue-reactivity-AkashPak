<template> 

<div>
<PushEen
v-for="cat in pusheenthecatthriftshop"
:key= "cat.name"
:push="cat"
@addtocart="Additem"
/>
</div>
</template>

<script setup> 
import PushEen from '@/components/PushEen.vue';
import PusheenCart from '@/components/PusheenCart.vue';


const pusheenthecatthriftshop= [
{
    name: "MerPusheen",
    Type: "Water",
    img: "https://cdn.shopify.com/s/files/1/0057/8182/products/mini-mermaid-pink.png?v=1499985441"
  };
  {
    name:"CinnPusheen",
    Type: 'Food',
    img:"https://i.pinimg.com/736x/97/56/f0/9756f009fc508b7650bdfdca4f1675b6.jpg",
  };
  {
    name:"SmorPusheen",
    Type: 'Food',
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/Pusheen_S_mores_Squisheen_021_web_1000x1000.jpg?v=1673384811",
  };
  {
    name:"RainbowPusheen",
    Type: "Normal",
    img:"https://i.pinimg.com/736x/36/b4/ac/36b4ac0154207a8f976f5cbf00f473c9.jpg",
  },
  {
    name:"CookiePusheen",
    Type: "Normal",
    img:"https://www.teslastoys.com/wp-content/uploads/2017/03/PUS-PT001-800x800.jpg",
  };
  {
    name:"SlothAndCat",
    Type: "Tog",
    img:"https://i.pinimg.com/originals/44/94/b1/4494b1456a0fb26f54d6df7338cc1bf9.png",
  };
  {
    name:"MiniNem",
    Type: "Tog",
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/group_classic_plush_004_700x700.png?v=1551139427",
  },  
  {
    name:"F&F";
    Type: "Tog";
    img:"https://pbs.twimg.com/media/Fx84z17XoAAWjtc.jpg";
  },  
  {
    name:"CandyPusheen";
    Type: "Normal";
    img:"https://cdn.shopify.com/s/files/1/0057/8182/products/candy-cane-plush-1_760x.png?v=1541111705%27";
  };
  {
    name:"BdayColorPusheen";
    Type: "Normal";
    img:"https://i.pinimg.com/736x/5a/4f/18/5a4f181aa0396d2e44b20ee1f3364bc1.jpg";
  };
  {
    name:"FancyPusheen";
    Type: "Normal";
    img:"https://i5.walmartimages.com/asr/314d123a-321c-4366-ab27-2ebcad7cdd84_1.34a987f055ba93807aef551077e7ced6.jpeg";
  };
  {
    name:"DetectivePusheen";
    Type: "Normal";
    img:"https://th.bing.com/th/id/OIP.NqLGjMeB7qMujvOL_d7nOAHaHa?rs=1&pid=ImgDetMain";
  };
  {
    name:"PterodactylPusheen";
    Type: "Dinosaur";
    img:"https://i5.walmartimages.com/asr/aff24023-54c4-4983-a16c-8137cc15f9d9.ca8183f8fe724798a1a6fee9acd57bf5.jpeg";
  };
  {
    name:"LochnessPusheen";
    Type: "Water";
    img:"https://i.pinimg.com/736x/0e/2b/59/0e2b59adc126186bf4bda32be66ec232.jpg";
  };
  {
    name:"NarwhalPusheen";
    Type: "Water";
    img:"https://cdn11.bigcommerce.com/s-0kvv9/images/stencil/1920w/products/263156/366956/pushnarwhal13__51664.1528912194.jpg?c=2";
  };
  {
    name:"TrexPusheen";
    Type: "Dinosaur";
    img:"https://i.pinimg.com/originals/e9/6d/5a/e96d5a19114a6bbab9c873fad69b0332.png";
  },
  {
    name:"SealPusheen";
    Type: "Water";
    img:"https://www.artbox.co.uk/images/Pusheen_Plush_Seal_1_400.jpg";
  },];
 /*  const cartItems=ref([])
  Additem= (item) =>{
    cartItems.value.push(item);
  } */

</script>


