<template>
    <ul class="liste">
        <li v-for="(fruit, index) in fruits" v-bind:key="index"> {{ fruit }} </li>
    </ul>
</template>
<script>
    export default {
        nom: 'Liste-1',
        data(){
            return {
                fruits: ['fraise', 'papaye', 'orange', 'citron']
            }
        }
    }

</script>

<style scoped src="./Liste-1.css">

</style>

