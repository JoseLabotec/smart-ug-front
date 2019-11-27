<template>
  <v-app>
    <v-content>
      <Login/>
      <menuPrincipal/>
      <RegistroGDO/>
      <RegistroUGP/>
      <RegistroUGEF/>
    </v-content>
  </v-app>
</template>

<script>
import menuPrincipal from './components/menuPrincipal';
export default {
  name: 'App',

  components: {
   menuPrincipal,
  },

  data: () => ({
    
  }),
};
</script>
