<template>
    <v-card dark class="pa-md-4 mx-lg-auto" color="blue">
        <h3>
            {{ greeting }}
        </h3>
    </v-card>
</template>

<script>

export default {
    name: 'GuideCard',
    data: function () {
        return {
            greeting: "Welcome to phoebe",
            info: "Let's take you through the core functions of our application!"
        }
    }
}

</script>