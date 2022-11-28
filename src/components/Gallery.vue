<template>
    <v-container class="my-5">
        <v-row justify="center">
            <v-col cols="12" class="text-center">
                <v-subheader class="text-md-h4 text-lg-h4 text-h5 justify-center">Gallery  </v-subheader>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit! </p>
            </v-col>
            <v-col
                v-for="n in 9"
                :key="n"
                class="d-flex child-flex"
                cols="6" lg="2" md="3" sm="3"
            >
                <v-img
                    :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
                    :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                    aspect-ratio="1"
                    class="grey lighten-2"
                >
                    <template v-slot:placeholder>
                    <v-row
                        class="fill-height ma-0"
                        align="center"
                        justify="center"
                    >
                        <v-progress-circular
                        indeterminate
                        color="grey lighten-5"
                        ></v-progress-circular>
                    </v-row>
                    </template>
                </v-img>
                </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name:"Gallery",
    data:() => ({

    })
}
</script>

