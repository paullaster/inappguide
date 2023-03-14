<template>
    <v-container>
        <v-card v-for="tip in tips" :key="tip.name" dark color="blue">
            <v-card-text>
                {{ tip.info }}
            </v-card-text>
            <div class="px-2">
                <v- class="ml-0">CLOSE</v->
                <v-btn class="info mr-0">NEXT</v-btn>
            </div>
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