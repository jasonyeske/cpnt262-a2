<template>
    <div>

<FullScreenCardLayout :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>




import FullScreenCardLayout from "./FullScreenCardLayout.vue";
const cardText = {

title: "Back to Practice",
preview: "The Junior League finally back to practicing again after not being able to play for two years with the covid outbreaks. Their first practice on October 12, 2021 meant a lot to everyone.",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1512755458728-b8f3c3e46439?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80"

}


</script>