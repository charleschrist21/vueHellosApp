<template>
  <div class="about">
    <Title msg="admin" />
  </div>
</template>

<script>
// @ is an alias to /src
import Title from '@/components/title.vue';

export default {
  name: 'about',
  components: {
    Title,
  },
};
</script>
