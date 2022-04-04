<template>
    <div>

<ReuseSmallCard :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>



import ReuseSmallCard from "../ReuseSmallCard.vue"
const cardText = {

title: "Womens World Cup",
preview: "The final game is being played Wednesday, and we got to interview the players",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1522602043785-821a161a5238?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=717&q=80"

}


</script>