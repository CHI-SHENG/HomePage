<template>
    <v-container>
        <v-row>
            <v-col cols="12" lg="6" md="6" sm="6">
                <v-img src="../assets/meettalk.png" contain></v-img>
            </v-col>
            <v-col cols="12" lg="6" md="6" sm="6">
                <v-subheader class="text-md-h4 text-lg-h4 text-h5">About us</v-subheader>
                <p class="text-md-subtitle-1 text-lg-subtitle-1 text-subtitle-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                <v-list>
                    <v-list-item>
                        <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                        <v-list-item-subtitle>Lorem ipsum dolor sit amet, consectetur adipiscing elit</v-list-item-subtitle>
                    </v-list-item>
                    <v-list-item>
                        <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                        <v-list-item-subtitle>Lorem ipsum dolor sit amet, consectetur adipiscing elit</v-list-item-subtitle>
                    </v-list-item>
                    <v-list-item>
                        <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                        <v-list-item-subtitle>Lorem ipsum dolor sit amet, consectetur adipiscing elit</v-list-item-subtitle>
                    </v-list-item>
                </v-list>
                <p class="text-md-subtitle-1 text-lg-subtitle-1 text-subtitle-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>
export default {
    name:"About",
    data:()=>({
        
    })
}
</script>