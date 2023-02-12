<template>
  <div class="wrapper" ref="wrapper">
    <ul class="content">
      <li v-for="item in data">{{ item }}</li>
    </ul>
  </div>
</template>
 
<script>
  import BScroll from 'better-scroll'
  export default {
    data() {
      return {
        data: 30
      }
    },
    created() {
      // requestData().then((res) => {
      //   this.data = res.data
      //   this.$nextTick(() => {
      //     this.scroll = new Bscroll(this.$refs.wrapper, {})
      //   })
      // })
    }
  }
</script>