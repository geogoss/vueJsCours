<template>
    <div>
        <p> {{ txt }} </p>
        <liste></liste>
    </div>
</template>
<script>

import Liste from '../Liste/Liste-1.vue'

    export default {
        nom: 'contenu-1',
        data: function(){
            return {
                txt: 'Je suis le contenu'
            }
        },
        components: {
            'liste': Liste
        }
    }

</script>
<style scoped src="./Contenu-1.css">

</style>