<template>
    <div>
        <navbarLog title="Hellos" text="Sign In"/>
        <img src="../assets/uu.png" class="img-bg">

        <h1 class="txt-signup">Sign Up</h1>
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
.txt-signup{
    font-family: Lobster;
    font-size: 24px;
    color: #753DBD;
    position: absolute;
    margin-left: 54px;
}
.img-bg{
  position: fixed;
  margin-left: 50%;
  margin-top: -50px;
}
</style>
