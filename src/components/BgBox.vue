<template>
  <div class="bg-box">
      <!-- <div class="bg"></div> -->
      <div class="bg-content">
        <slot></slot>
      </div>
    </div>
</template>

<script>
  export default {
    name: 'BgBox'
  }
</script>

<style lang="less" scoped>
  .bg-box{

    .bg{
      height: 100px;
      background-color: #ccc;
    }

    // .bg-content{
    //   margin: 0 10px;
    //   position: relative;
    //   top: 100px;
    //   // background-color: #000;
    //   border-radius: 8px;
    //   padding: 10px;
    //   overflow: hidden;
    // }
    .bg-content{
      margin: 0 10px;
      position: relative;
      top: 100px;
      background-color:  #3a3b8b;
      border-radius: 8px;
      padding: 10px;
      overflow: hidden;
    }
  }
</style>