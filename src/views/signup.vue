<template>
    <div>
        <navbarLog title="Hellos" text="Sign In"/>
        <img src="../assets/uu.png" class="img-bg">
    </div>
</template>

<script>
import navbarLog from '@/components/navbarLog.vue';

export default {
  name: 'signup',
  components: {
    navbarLog,
  },
};
</script>

<style scoped>
.img-bg{
  position: fixed;
  margin-left: 50%;
  margin-top: -50px;
}
</style>
