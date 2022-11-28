<template>
    <v-app-bar
      style="padding: 0px 150px"
      app
      color="white"
      light
      elevation="10"
      elevate-on-scroll
    >
      <v-toolbar-title class="font-weight-black blue--text text-md-h4">
        Web Sheng
      </v-toolbar-title>
      <v-spacer></v-spacer>

      <v-list class="d-flex align-center">
        <v-list-item link v-for="(menu,index) in menus" :key="index" :to="menu.route">
          <v-list-item-title>
            {{menu.title}}
          </v-list-item-title>
        </v-list-item>
        <v-btn text>
          <v-icon>
            mdi-magnify
          </v-icon>
        </v-btn>
        <v-btn outlined color="success">Get Start</v-btn>
      </v-list>
    </v-app-bar>

</template>

<script>
export default {
    name:"Header",
    data: () => ({
        menus:[
        { title:"Home", route:"home"  },
        { title:"Abous us", route:"abous-us"  },
        { title:"Profolio", route:"profolio"  },
        { title:"Project",  route:"project" },
        { title:"Gallery",  route:"gallery" },
        { title:"Contact",  route:"contact" },
        ]
    }),
    
}
</script>