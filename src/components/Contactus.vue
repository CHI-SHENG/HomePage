<template>
    <v-container class="my-5">
            <v-row justify="center">
                <v-col cols="12" class="text-center">
                    <v-subheader class="text-md-h4 text-lg-h4 text-h5 justify-center">Contact  </v-subheader>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit! </p>
                </v-col>
                <v-col cols="12" lg="6" md="6" sm="6">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3747121.81958051!2d120.0843006!3d23.485750050000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x346ef3065c07572f%3A0xe711f004bf9c5469!2z5Y-w54Gj!5e0!3m2!1szh-TW!2stw!4v1669645782120!5m2!1szh-TW!2stw" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </v-col>
                <v-col cols="12" lg="6" md="6" sm="6">
                    <v-form
                        ref="form"
                    >
                        <v-text-field
                            v-model="Contact.name"
                            :counter="10"
                            label="Name"
                            required
                        ></v-text-field>

                        <v-text-field
                            v-model="Contact.email"
                            label="E-mail"
                            required
                        ></v-text-field>
                        <v-textarea label="Message" v-model="Contact.message">

                        </v-textarea>
                        <v-btn
                            color="success"
                            class="mr-4"
                        >
                            Send
                        </v-btn>
                    </v-form>
                </v-col>
            </v-row>
    </v-container>
</template>
<script>
export default {
    name:"Contactus",
    data:() => ({
        Contact:{
            name:"",
            email:"",
            message:""
        }
    }),
}
</script>