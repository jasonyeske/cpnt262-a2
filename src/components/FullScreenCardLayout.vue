<template>

    <div class="  bg-cover bg-bottom relative border-2 border-black overflow-hidden rounded-3xl" >

<h1 class="text-3xl text-center">{{ props.content.title }}</h1>
<img class=" mr-auto ml-auto " :src="props.img.url" />
<p class="text-center">{{props.content.preview}}</p>
<div class="flex flex-col">
<button class="bg-gray-300 hover:bg-sky-400">
   Enter Page
</button>
</div>
    </div>
    
</template>

<script setup>

import { defineProps } from 'vue';
const props = defineProps({
   content: {
      type: Object,
   
   } ,
   img:{
       type: Object,
   },

});

</script>

