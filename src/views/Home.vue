<template>
  <v-app>
    <TopBar class="index"/>
    <DashBoard />
    <Footer />
  </v-app>
</template>

<script>
  import TopBar from '../components/TopBar';
  import DashBoard from '../components/DashBoard';
  import Footer from '../components/Footer';

  export default {
    name: 'Home',

    components: {
      TopBar,
      DashBoard,
      Footer,
    },
  }
</script>

<style scoped>

.index {
  z-index: 9999;
}
</style>
