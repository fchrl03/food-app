<template>
  <div class="home">
    <NavbarHeader />
    <div class="container">
      <HeroDashboard />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarHeader from '@/components/Navbar.vue';
import HeroDashboard from '@/components/HeroDashboard.vue';

export default {
  name: 'HomeView',
  components: {
    NavbarHeader,
    HeroDashboard,
  },
};
</script>
