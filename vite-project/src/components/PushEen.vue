<template>
  <div class="flex-container">
 <h1>{{ kat.name }} </h1>
 <img class="img" :src="kat.img" alt=""/>
 <button @click="addItem">Add to Kitty Kart</button>
  </div>
 
 </template>
 
  <script setup>
 import { defineEmits ,defineProps } from 'vue'; 
 
 const props = defineProps({
   kat: Object
 });
 const emit = defineEmits(['AddItem']);
 const addItem=()=>{
   emit('AddItem' , props.kat);
 };
 
 </script>
 
 
  <style scoped>
  .img{
 height:20% ;
 width:30%
  };
  .flex-container{
   display: flex;
 flex-wrap: wrap;
   flex-direction: column;
   
  }
 </style>
 
 
 
 