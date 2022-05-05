<template>
  <div class="offering">
    <div class="introduce">
      <n-card title="总交易量"> $1,025,837,390 </n-card>
      <n-card title="IGO项目"> 17 </n-card>
      <n-card title="质押总量"> $71,218,863 </n-card>
      <n-card title="总参与人数"> 264,867 </n-card>
    </div>
  </div>
  <div class="current_nft">
    <div class="current_nft_top">
      <div class="current_nft_top_left">左边</div>
      <div class="current_nft_top_right">空白</div>
    </div>
    <div class="current_nft_middle">中间</div>
    <div class="current_nft_botton">底部</div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class Offering extends Vue {}
</script>

<style>
body {
  width: 100%;
  height: 100%;
}

.n-card {
  max-width: 300px;
  margin: 5px;
  border: 0;
  padding: 0;
}
.introduce {
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.current_nft {
  width: 100%;
  align-items: center;
  justify-content: center;
}
.current_nft_top {
  width: 100%;
  border: 1px solid #ff6699;
}
.current_nft_top_left {
  width: 40%;
  height: 100px;
  border: 1px solid #ff6699;
}
.current_nft_top_right {
  width: 60%;
  height: 100px;
  border: 1px solid #ff6699;
}
.current_nft_middle {
  width: 100%;
  height: 100px;
  border: 1px solid #ff6699;
}
.current_nft_bottom {
  width: 100%;
  height: 100px;
  border: 1px solid #ff6699;
}
</style>
