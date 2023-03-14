<template>
    <v-container>
        <v-card v-for="tip in tips" :key="tip.name">
            <v-card-text>
                {{ tip.info }}
            </v-card-text>
            <v-btn flat>CLOSE</v-btn>
            <v-spacer></v-spacer>
            <v-btn flat class="info">NEXT</v-btn>
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