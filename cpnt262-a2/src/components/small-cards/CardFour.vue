<template>
    <div>

<ReuseSmallCard :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>



import ReuseSmallCard from "../ReuseSmallCard.vue"
const cardText = {

title: "Number One Draft Pick",
preview: "An interview with the expected number one draft pick of 2023",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1638128505201-05372935efa1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=688&q=80"

}


</script>