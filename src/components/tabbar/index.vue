<template>
  <div class="g-tabbar">
    <router-link class="g-tabbar-item" to="/home" ref="p" @click.native="qwe">
      <i class="iconfont icon-home"></i>
      <span>商城</span>
    </router-link>
    <router-link class="g-tabbar-item" to="/category">
      <i class="iconfont icon-category"></i>
      <span>分类</span>
    </router-link>
    <router-link class="g-tabbar-item" to="/search">
      <i class="iconfont icon-search"></i>
      <span>搜索</span>
    </router-link>
    <router-link class="g-tabbar-item" to="/personal">
      <i class="iconfont icon-personal"></i>
      <span>我</span>
    </router-link>
  </div>
</template>

<script>
  export default {
    name: 'FootBar',
    methods: {
      showtext: function () {
        console.log(this.$refs);
        this.qwe();
      },
      qwe: function () {
        console.log('111');
      }
    }
  };
</script>

<style lang="scss" scoped>
  @import "~assets/scss/mixins";

  .router-link-active {
    color: $link-active-color;
  }

</style>
