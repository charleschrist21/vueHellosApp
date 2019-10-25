<template>
  <div>
    <NavbarLog title="Hellos" text="Sign In"/>
    <img src="../assets/uu.png" class="img-bg">

    <h1>Welcome</h1>
    <p class="h2-2">Please Login</p>
    <div class="user-control">
        <img src="../assets/loginAsset/user-modal.png" alt="" class="user-login-ic">
        <p class="name-login">Charles Christian Adi Mulyono</p>
    </div>

    <form action="">
        <input type="password" name="" id="" class="password-inp" placeholder="Enter Password">
        <img src="../assets/loginAsset/pass.png" alt="" class="password-ic">
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
.password-ic{
    position: absolute;
    margin-top: 115px;
    margin-left: 510px;
}
.password-inp{
    height: 41px;
    width: 335px;
    position: absolute;
    margin-top: 100px;
    margin-left: 160px;
    border-radius: 10px;
    border: 0px;
    border: 1px solid #A8A8A8;
    color: #B5B5B5;
    font-size: 18px;
    padding-left: 15px;
    padding-right: 30px;
    font-weight: bold;
}
.user-control{
    width: 50%;
    height: 50px;
    align-content: center;
    align-items: center;
}
.name-login{
    margin-left: auto;
    margin-right: auto;
    display: block;
    font-size: 18px;
    font-weight: bold;
    width: 50%;
    text-align: center;
    position: absolute;
}
.user-login-ic{
    width: 80px;
    height: 80px;
    margin-left: auto;
    margin-right: auto;
    display: block;
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
