<template>
<div>
  <div class="wrap">
    <div>
      <ul class="List">
        <li class="ListItem">
          <i>*</i>
          <span>30天无忧退货</span>
        </li>
        <li class="ListItem">
          <i>*</i>
          <span>48小时快速退款</span>
        </li>
        <li class="ListItem">
          <i>*</i>
          <span>满88元免邮费</span>
        </li>
      </ul>
    </div>

    <div class="CartSpace"></div>
    <div class="CartImg">
      <img src="../../img/cart.png" alt="">
    </div>
    <div class="CartAdd">
      <span>去添加点什么吧</span>
    </div>
      <span class="CartLogin">登录</span>

  </div>
</div>
</template>


<script>


</script>


<style>
.wrap{
  width: 100%;

}
  .List{
    width: 100%;
    height: 1rem;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    margin-top: 0.2rem;
    font-size: 0.35rem;

  }
  .ListItem{
    margin-right: 0.4rem;
  }
.CartSpace{
  width: 100%;
  height: 3rem;
}
.CartImg{
  background-repeat: no-repeat;
  background-size: 100%;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.CartAdd{
  width: 100%;
  height: 0.8rem;
  font-size: 0.5rem;
  line-height: 0.5rem;
  color: #878787;
  text-align: center;
  vertical-align: middle;
}
  .CartLogin{
    width: 80%;
    height: 1.2rem;
    background-color: #cc0031;
    font-size: 0.8rem;
    line-height: 0.8rem;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #ffffff;
    margin-left: 1rem;
    margin-top: 1.5rem;
  }

</style>
