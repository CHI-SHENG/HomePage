<template>
    <v-footer
        padless
    >
        <v-col cols="12">
            <v-row justify="center">
                <v-col cols="12" lg="4" md="7" sm="8" class="text-center">
                    <v-toolbar-title>Web Burden</v-toolbar-title>
                    <v-card-text>
                        <v-btn
                            v-for="icon in icons"
                            :key="icon"
                            class="mx-4 "
                            icon
                        >
                        <v-icon size="24px">
                            {{ icon }}
                        </v-icon>
                        </v-btn>
                    </v-card-text>
                    <v-subheader>Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum.</v-subheader>
                    <v-form>
                        <v-text-field label="Email" outlined dense></v-text-field>
                        <v-btn outlined rounded color="success"> Subscribe us</v-btn>
                    </v-form>
                </v-col>
            </v-row>
        </v-col>
        <v-card
            flat
            tile
            class=" lighten-1 black--text text-center"
            color="blue"
            dark
        >
        
        <v-card-text class="pt-0">
            Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="white--text">
            {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
        </v-card-text>
        </v-card>
    </v-footer>
</template>

<script>
export default {
    name:"Footer",
    data:()=>({
        icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
}
</script>