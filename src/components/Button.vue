<template >
  <button @click="oneCliCK()" :style="{ background: color }" class="btn">{{ text }}</button>
</template>
<script>
export default {
  name: "Button",
  props: {
    text: {
      type: String,
      default:"Add Task",
    },
    color: {
      type: String,
      default:"Green",
    },
  },
  methods:{
    oneCliCK(){
        alert('THIS IS')
    }
  }
};
</script>
<style lang="css">
</style>