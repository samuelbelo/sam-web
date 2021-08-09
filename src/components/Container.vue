<template lang="pug">
  v-fade-transition(
    mode="out-in"
    type="animation")
    v-content
      v-container(fluid fill-height)
        v-layout(align-center justify-center)
          v-flex(md10 sm12)
            v-layout(wrap)
              v-flex(md4)
                Sidebar
              v-flex(md8)
                Content

</template>
<script>
import Sidebar from "@/components/Sidebar/Sidebar";
import Content from "@/components/Content/Content";
  export default {
    name: 'Container',
    components: {
      Sidebar,
      Content
    },
    data() {
      return {

      }
    },
  }
</script>
