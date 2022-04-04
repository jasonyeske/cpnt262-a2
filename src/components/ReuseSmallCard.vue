<template>

    <div class="flex flex-col border-2  border-black rounded-3xl  m-6 overflow-hidden sm:w-80 md:w-80  ">

<h1 class="text-3xl text-center">{{ props.content.title }}</h1>
<img class="h-96 mr-auto ml-auto " :src="props.img.url" />
<p class="text-center">{{props.content.preview}}</p>
<button class="bg-gray-300 hover:bg-sky-400">
   Enter Page
</button>
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

