<template>
    <v-container>
        <v-card v-for="tip in tips" :key="tip.name">
            {{ tip.info }}
        </v-card>
    </v-container>
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