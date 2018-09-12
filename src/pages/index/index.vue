<template>
  <div>
    <div class="header">
      <icon type="search" size="20"></icon>
      <input type="text" placeholder="搜索">
    </div>
  </div>
</template>

<script>


export default {
 
}
</script>

<style lang="less">
    .header {
      background-color: #f10250;
      padding: 20rpx 16rpx;
      position: relative;
      icon{
        position: absolute;
        top: 34rpx;
        left: 50%;
        transform:translate(-200%);
        z-Index: 998;
      }
      input {
        height: 60rpx;
        width: 100%;
        background-color: #fff;
        text-align:center;
        border-radius: 6rpx;
        font-size: 26rpx;
      }
    }
</style>
