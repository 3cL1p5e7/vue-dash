<template>
  <div :class="b()">
    Here will be a help page
  </div>
</template>
<script>
export default {
  block: 'help'
};
</script>
<style scoped lang="sass">
.help
  display: flex
  flex-direction: row
  justify-content: center
  padding: 10vh 0
  font-size: $font_size_l
  position: absolute
  top: 0
  left: 0
  right: 0
  bottom: 0
</style>