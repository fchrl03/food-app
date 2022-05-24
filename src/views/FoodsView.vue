<template>
  <div>
    <NavbarHeader />
    <h2>Foods</h2>
  </div>
</template>

<script>
import NavbarHeader from '@/components/Navbar.vue';

export default {
  name: 'FoodsView',
  created() {
    document.title = 'Foods List';
  },
  components: {
    NavbarHeader,
  },
};
</script>

<style></style>
