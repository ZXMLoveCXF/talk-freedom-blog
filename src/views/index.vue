<template>
  <div class="color">这是{{ page }}页面</div>
</template>
<style lang="sass" scoped>
    $a:red;
    .color{
      $a:blue;
      color: $a;
    }
    .color-red{
color: $a;
    }
</style>

<script>
  export default {
    data () {
      return {
        page: 'index'
      }
    }
  }
</script>

