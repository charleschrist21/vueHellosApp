<template>
    <div class="quotes">
        <h1>"{{ title }}"</h1>
    </div>
</template>

<script>
export default {
  name: 'quotes',
  props: {
    title: String,
  },
};
</script>

<style scoped>
h1{
    position: absolute;
    width: 50%;
    text-align: center;
    margin-top: 250px;
    font-size: 24px;
}
</style>
