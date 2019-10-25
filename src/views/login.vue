<template>
  <div>
    <NavbarLog title="Hellos" text="Sign In"/>
    <img src="../assets/uu.png" class="img-bg">

    <h1>Welcome</h1>
    <p class="h2-2">Please Login</p>

    <form action="">
      <img src="../assets/loginAsset/next.png" alt="" class="next-ic">
      <input type="text" name="text" id="" class="email-inp" placeholder="Username">
      <img class="email-ic" src="../assets/loginAsset/email-@.png" alt="">
    </form>
    <quotes title="You are Greates"/>
  </div>
</template>

<script>
import NavbarLog from '@/components/navbarLog.vue';
import quotes from '@/components/quotes-bottom.vue';

export default {
  name: 'login',
  components: {
    NavbarLog,
    quotes,
  },
};
</script>

<style scoped>
.next-ic{
  margin-left: 530px;
  margin-top: 95px;
  position: absolute;
  z-index: 2;
  cursor: pointer;
}
.email-inp{
  width: 400px;
  height: 56px;
  position: absolute;
  margin-top: 80px;
  margin-left: 157px;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  border: 0px;
  border: 1px solid #A8A8A8;
  padding-left: 15px;
  font-size: 24px;
  color: #B5B5B5;
  padding-right: 10px;
  font-weight: bold;
}
.email-ic{
  margin-left: 96px;
  margin-top: 80px;
  position: absolute;
}
.h2-2{
  font-size: 18px;
  color: #9B9B9B;
  font-weight: bold;
  margin-left: 120px;
  margin-top: 120px;
}
.img-bg{
  position: fixed;
  margin-left: 50%;
  margin-top: -50px;
}
h1{
  font-family: Lobster;
  font-size: 48px;
  color: #753DBD;
  position: absolute;
  margin-left: 96px;
  margin-top: 50px;
}
</style>
