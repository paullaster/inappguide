<template>
    <v-card>
        {{ text }}
    </v-card>
</template>

<script>

export default {
    name: 'GuideCard',
    data: function(){
        return {
            text: "Welcome to phoebe!"
        }
    }
}

</script>