<template>
    <div>
        <ul class="liste">
            <li v-for="(fruit, index) in fruits" v-bind:key="index"> {{ fruit }} </li>
        </ul>

        <!-- <p>
            {{ prenom }}
        </p>
        <p>
            {{ insectes[2] }}
        </p> -->
        <p>
            {{ choses.table }}
        </p>


    </div>
</template>
<script>
export default {
    nom: 'Liste-1',
    data() {
        return {
            fruits: ['fraise', 'papaye', 'orange', 'citron']
        }
    },
    props: ['prenom', 'insectes', 'choses']
    
}

</script>

<style scoped src="./Liste-1.css">

</style>

