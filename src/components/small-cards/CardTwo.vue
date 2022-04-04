<template>
    <div>

<ReuseSmallCard :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>



import ReuseSmallCard from "../ReuseSmallCard.vue"
const cardText = {

title: "Playoff Bound",
preview: "This hockey team has made the playoffs for the first time in 30 years",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1616472726008-c5f6350eb96a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"

}


</script>