<template>
    <div>
    <v-app-bar
      color="white"
      dense
      light
      elevation="8"
    >

      <router-link to="/" >
      <v-img src="2.png" max-height="45" max-width="180"></v-img>
</router-link>

      <v-spacer></v-spacer>

      <!-- <v-btn text to="/docs">
        Docs
      </v-btn>


      <v-btn text to="/contact">
        Contact
      </v-btn> -->

      <v-btn icon target="_blank" href="https://github.com/chainscore">
        <v-icon>mdi-github</v-icon>
      </v-btn>


    </v-app-bar>
  </div>
</template>

<script>
export default {
    data(){
        return{
            options: [
                'Github',
                'Documentation'
            ]
        }
    }
}
</script>