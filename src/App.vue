<template>
  <v-app>
     <NavBar />
     <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar'
import './assets/stylesheets/main.css'

export default {
  name: 'App',
  components: { NavBar },
  data: () => ({

  }),
};
</script>
