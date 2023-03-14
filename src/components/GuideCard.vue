<template>
    <v-container>
        <v-card>
        <v-card-title >
            {{ greeting }}
        </v-card-title>
    </v-card>
    </v-container>
</template>

<script>

export default {
    name: 'GuideCard',
    data: function(){
        return {
            greeting: "Welcome to phoebe!",
            info: "Let's take you through the core functions of our application!"
        }
    }
}

</script>