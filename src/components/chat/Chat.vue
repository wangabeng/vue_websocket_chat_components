<template>
  <div class="chat">
    chat content
  </div>
</template>

<script>
export default {
  name: 'Chat',
  data () {
    return {
    }
  }
}
</script>

<style lang='stylus' rel='stylesheet/stylus'>
@import '~common/stylus/variable.styl'
.chat
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: $color-background;
</style>
