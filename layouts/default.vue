<template>
  <v-app dark>

   
     <Header />
   
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
 
     <Footer />
   
  </v-app>
</template>

<script>
import Header from '@/components/header/index.vue';
import Footer from '@/components/footer/index.vue';
export default {
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
  ,components:{
    Header,
    Footer,
  }
}
</script>
