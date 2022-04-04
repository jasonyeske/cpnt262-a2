<template>
    <div>

<ReuseSmallCard :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>



import ReuseSmallCard from "../ReuseSmallCard.vue"
const cardText = {

title: "The Impossible",
preview: "This hockey player pulled off this incredible move in a game against their division rivals",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1580748185659-ba000777cb96?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"

}


</script>