<template>
  <div class="header">
    <div class="back iconfont">&#xe624;</div>
    <div class="
search"><span class="search-icon iconfont">&#xe632;</span>请输入搜索内容</div>
    <div class="city">乌鲁木齐</div>
  </div>
</template>

<script>
    export default {
        name: "headers"
    }
</script>

<style scoped>
  .header{
    display: flex;
    height: .88rem;
    line-height: .88rem;
    background: #00bcd4;
    color: #fff;
  }
    .back{
      width: .58rem;
      text-align: center;
      font-size: .4rem;
      font-weight: bolder;
    }
    .search{
      flex: 1;
      height: .6rem;
      line-height: .6rem;
      margin: .14rem .2rem;
      padding-left: .4rem;
      background: #fff;
      border-radius: .1rem;
      color: #919191;
    }
      .search-icon{
        position: relative;
        top: .02rem;
        padding-right: .04rem;
      }
    .city{
      padding-right: .6rem;
      position: relative;
    }
      .city::before{
        position: absolute;
        top: .34rem;
        right: .2rem;
        content: '\0020';
        width: 0;
        height: 0;
        border-left: .14rem solid transparent;
        border-right: .14rem solid transparent;
        border-top: .14rem solid #fff;
      }
</style>
