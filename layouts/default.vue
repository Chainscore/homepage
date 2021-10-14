<template>
  <v-app dark>
    <Header />
    <v-main class="background">
        <Nuxt />
    </v-main>
    
    <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
      <v-spacer></v-spacer>
      <div>
        <a 
        class="white--text text-decoration-none" 
        target="_blank" 
        href="mailto:hello@chainscore.finance">
          hello@chainscore.finance
        </a>
      </div>
    </v-footer>
  </v-app>
</template>

<script>
import Header from '../components/Header.vue';

export default {
  components: {
    Header
  },
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>

<style scoped>
  .background{
    background-image: linear-gradient( 135deg, #FDEB71 10%, #F8D800 100%);
}
</style>