<template>
    <div class="container">
        <p> {{ txt }} </p>
        <!-- <liste v-bind:prenom="prenom"></liste> -->
        <!-- <liste v-bind:insectes="insectes"></liste> -->
        <liste v-bind:prenom="prenom"></liste>
        <suite-1></suite-1>
    </div>
</template>

<script>

import Liste from '../Liste/Liste-1.vue'
import Suite1 from '../Suite1/Suite-1.vue'

    export default {
        nom: 'contenu-1',
        data: function(){
            return {
                txt: 'Je suis le contenu',
                prenom: 'Geoffrey',
                insectes: ["fourmi", "abeille", "guèpe", "coléoptère"],
                choses: {
                    matelas: 1,
                    table: 3,
                    chaise: 9,
                    assiettes: 16
                }
            }
        },
        components: {
            'liste': Liste,
            'suite-1': Suite1
        }
                
    }

</script>
<style scoped src="./Contenu-1.css">

</style>