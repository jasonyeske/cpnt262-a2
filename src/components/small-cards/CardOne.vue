<template>
    <div>

<ReuseSmallCard :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>



import ReuseSmallCard from "../ReuseSmallCard.vue"
const cardText = {

title: "Huge Trade",
preview: "This hockey player was traded in a series of strange events to this team",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1567066245527-7097def64260?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"

}


</script>