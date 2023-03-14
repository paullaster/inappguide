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
            tips: [
                {
                    name: 'home screen',
                    info: "Let's take tour of the core functions of our application"
                }
            ]
        }
    }
}

</script>