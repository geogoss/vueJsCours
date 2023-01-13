<template>
    <div>
        <p> {{ txt }} </p>
        <!-- <liste v-bind:prenom="prenom"></liste> -->
        <!-- <liste v-bind:insectes="insectes"></liste> -->
        <liste v-bind:choses="choses"></liste>
    </div>
</template>

<script>

import Liste from '../Liste/Liste-1.vue'

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
            'liste': Liste
        }
    }

</script>
<style scoped src="./Contenu-1.css">

</style>