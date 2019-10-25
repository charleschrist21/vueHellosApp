<template>
    <div class="navbar">
        <h1>{{ title }}</h1>
        <a href="">{{ text }}</a>
    </div>
</template>

<script>
export default {
  name: 'navbar',
  props: {
    title: String,
    text: String,
  },
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lobster&display=swap');
.navbar{
    width : 50%;
    height : 52px;
    background-color : white;
    margin-top: -10px;
}
h1{
    font-family: 'Lobster', cursive;
    font-size: 24px;
    margin-left: 40px;
    margin-top: 16px;
    position: absolute;
}
a{
    font-size: 9px;
    text-decoration: none;
    color: white;
    position: absolute;
    left: 44%;
    padding: 6px 16px 6px 16px;
    margin-top: 20px;
    background-color: #3AA3AA;
    border-radius: 6px;
}
</style>
