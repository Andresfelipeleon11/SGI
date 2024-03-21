

<script lang="ts">

export default {
    components: {
        
    },
   setup(){
    let fruta = ['banana', 'maca', 'laranja', 'abacaxi'];

    return{
      fruta
    }
   }
}
</script>

<template>

   <ul v-for="(frutas, key) in fruta" :key="key">
    <li >{{ frutas }}</li>
   </ul>
   <h1>Hola</h1>
</template>


<style scoped>

</style>