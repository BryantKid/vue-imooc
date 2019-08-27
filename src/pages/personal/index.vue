<template>
<!--  <div class="personal">-->
<!--    ======================================================================<br><br>-->

<!--    Copyright (C) 2018-2019 tangdongliang<br>-->
<!--    All rights reserved<br><br>-->

<!--    filename :在线商城<br>-->
<!--    description : 防淘宝京东在线商城。<br><br>-->

<!--    created by 汤东亮 at  11/09/2018 18:41:28<br>-->
<!--    http://www.tdleon.com/<br><br>-->

<!--    ======================================================================<br>-->
<!--  </div>-->
  <div>
    <img src="./br.png" alt="br" class="brpic">
    <div>
      <div class="brtext">BR在线商城</div>
      <div class="brtext">Description : 防淘宝京东在线商城</div>
    </div>
    <div class="brtext1">
      <div class="brtext">Created By 汤东亮 at  11/09/2018 18:41:28</div>
      <dvi class="brtext">Copyright (C) 2018-2019 tangdongliang</dvi>
    </div>
  </div>
</template>

<script>

  export default {
    name: 'Personal'
  };
</script>

<style lang="scss" scoped>
.brpic {
  margin: 30% 0 0 25%;
  height: 50%;
  width: 50%;
}
  .brtext{
    text-align: center;
    font-size: large;
    height: 30px;
    /*background: #de181b;*/
  }
  .brtext1 {
    text-align: center;
    font-size: large;
  }
</style>
