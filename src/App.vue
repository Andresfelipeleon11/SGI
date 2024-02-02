<script lang="ts">

let fruta = ['fresa', 'mango', 'kiwi']




</script>

<template>

   <ul v-for="(frutas, key) in fruta" :key="key">
    <li >{{ frutas }}</li>
   </ul>

</template>


<style scoped>

</style>