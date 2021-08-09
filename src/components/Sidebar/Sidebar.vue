<template lang="pug">
  v-card(tile color="grey darken-3")
    v-card-text.white--text
      Avatar
      div.text-sm-center.mb-4.mt-3
        h1 Samuel Belo
        span A technology-loving and passionated developer...

</template>

<script>
import Avatar from "@/components/Sidebar/Avatar";
export default {
    name: "Sidebar",
    components: {
      Avatar
    }
}
</script>

<style scoped>

</style>