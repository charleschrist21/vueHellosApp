<template>
    <div class="title">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
  name: 'title',
  props: {
    msg: String,
  },
};
</script>