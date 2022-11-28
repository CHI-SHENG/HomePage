<template>
    <v-container class="pt-10">
        <v-row>
            <v-col cols="12" lg="6" md="6" sm="6">
                <h2 class="text-md-h2 text-lg-h2 text-h4  font-weight-black">Welcome to our Vuetify App</h2>
                <p class="grey--text my-14">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                <v-btn color="success" rounded class="mr-6">Get started</v-btn>
                <v-btn color="indigo" class="white--text" rounded>
                    <v-icon>mdi-play-circle</v-icon>
                    Watch Video
                </v-btn>
            </v-col>
            <v-col cols="12" lg="6" md="6" sm="6">
                <v-img src="../assets/work3.jpeg" ></v-img>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>
export default {
    name:"HeroComponents",
}
</script>