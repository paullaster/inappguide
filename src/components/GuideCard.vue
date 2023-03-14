<template>
    <v-container fluid class="pa-0">
        <v-card dark color="blue">
                <h2 class="text-h4">
                    {{ greeting }}
                </h2>
                <p class="pa-2 d-flex justify-center">
                    {{ info }}
                </p>
                <v-btn class="black white--text">
                    close
                </v-btn>
                <v-btn depressed color="primary">
                    next
                </v-btn>
            <v-spacer></v-spacer>
        </v-card>
    </v-container>
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