<template lang="pug">
  v-app
    v-main.layout-background
      router-view
</template>
<script>
export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
<style>
.layout-background {
  background-color: #e8e8e8;
}
</style>