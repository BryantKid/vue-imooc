<template>
  <div class="category">
    <header class="g-header-container">
      <category-header/>
    </header>
    <Test class="test"></Test>
  </div>
</template>

<script>
  import CategoryHeader from './header';
  import Test from './flow';

  export default {
    name: 'Category',
    components: {
      CategoryHeader,
      Test
    }
  };
</script>

<style lang="scss" scoped>
  @import "~assets/scss/mixins";

  .category {
    overflow:hidden;
    width:100%;
    height:100%;
    background-color: $bgc-theme;
  }
  .test {
    padding: 50px 0 0 0;
  }
</style>
