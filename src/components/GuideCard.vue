<template>
    <v-container>
        <v-card v-for="tip in tips" :key="tip.name" dark color="blue" class="pb-4">
            <v-card-text>
                {{ tip.info }}
            </v-card-text>
            <div class="px-4 d-flex flex-row justify-space-between">
                <v-btn class="d-block" @click="destroy">
                    CLOSE
                </v-btn>
                <v-btn class="d-block info">NEXT</v-btn>
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
                    info: "Let's take a tour of the core functions of our application"
                }
            ]
        }
    },
    props: {
        destroy: {
            type: Function,
            required: true
        },
    }
}

</script>