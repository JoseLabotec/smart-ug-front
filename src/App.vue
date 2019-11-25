<template>
  <v-app>
    <v-content>
      <HelloWorld/>
      <vistageneral/>
      <RegistroGDO/>
    </v-content>
  </v-app>
</template>

<script>
import RegistroGDO from './components/RegistroGDO';
export default {
  name: 'App',

  components: {
   RegistroGDO,
  },

  data: () => ({
    
  }),
};
</script>
