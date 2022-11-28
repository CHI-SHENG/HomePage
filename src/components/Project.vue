<template>
    <v-container class="my-5">
        <v-row justify="center">
            <v-col cols="12" class="text-center">
                <v-subheader class="text-md-h4 text-lg-h4 text-h5 justify-center">Project </v-subheader>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit! </p>
            </v-col>
            <v-col cols="12" lg="3" md="4" sm="6" v-for="i,index in 3" :key="index">
                <v-card
                    class="mx-auto my-12"
                    max-width="374"
                >
                    <v-img
                    height="250"
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSGKKoK75ov9LqjViuGWWR4Jhry27_HWaH4EDSw0wGBTw3QnwFrjIz7ALP85S9cRfMOF9Y&usqp=CAU"
                    ></v-img>

                    <v-card-title>Web development</v-card-title>

                    <v-card-text>


                    <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
                    </v-card-text>
                    <v-divider class="mx-4"></v-divider>
                    <v-card-actions>
                        <v-btn
                            color="success"
                        >
                            Views Detail
                        </v-btn>
                        <v-spacer></v-spacer>
                        <v-rating
                            :value="4.5"
                            color="amber"
                            dense
                            half-increments
                            readonly
                            size="14"
                            ></v-rating>
                    </v-card-actions>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name:"Project",
    data:() => ({

    }),

}
</script>