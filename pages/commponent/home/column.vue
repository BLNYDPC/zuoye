<template>
 <view class="column">
    <view class="column_left">https://img10.360buyimg.com/n1/s450x450_jfs/t1/124942/17/8199/126410/5f1fa2acEc46d1020/883ca90ac6bff77f.jpg" mode="scaleToFill" class="left_img"></image>
    </view>
    <view class="colum_right">
      <image src="https://img10.360buyimg.com/n1/s450x450_jfs/t1/124942/17/8199/126410/5f1fa2acEc46d1020/883ca90ac6bff77f.jpg" class="right_img"></image>
      <image src="https://img10.360buyimg.com/n1/s450x450_jfs/t1/124942/17/8199/126410/5f1fa2acEc46d1020/883ca90ac6bff77f.jpg" style="margin-top: 12upx" class="right_img"></image>
    </view>
  </view>
</template>

<script>

export default {
  data() {
    return {};
  },

  components: {},
  props: {},
  methods: {}
};
</script>
<style lang="scss" scoped>
.column{
  height: 400upx;
  width: 94%;
  overflow: hidden;
  margin: 0 3%;
  margin-top: 15upx;
}
.column_left{
  height: 100%;
  width: 40%;
  float: left;
  .left_img{
    width: 100%;
    height: 100%;
    display: block;
  }
}
.colum_right{
  float: right;
  width: 58%;
  .right_img{
    width: 100%;
    height: 196upx;
    display: block;
  }
}
</style>