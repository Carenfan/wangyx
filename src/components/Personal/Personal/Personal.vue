<template>
  <div>
    <section class="LoginWrap">
       <div class="LoginImgWrap">
         <div class="LoginImg">
           <img src="../../img/login/logo(1).png" alt="">
         </div>
       </div>
      <div class="ToLogin">
        <div class="Numlogin NumloginSelect">
          <i class="LoginPN"></i>
          <span> 手机号码登录</span>
        </div>
        <div class="Maillogin">
          <i  class="LoginM"></i>
          <span> 邮箱账号登录 </span>
        </div>
        <a class="QRej">手机号快捷注册 > </a>
      </div>
      <div class="LoginType">
        <div class="Wechart">
          <img src="../../img/login/weix.png">
          <span>微信</span>
        </div>
        <div  class="Q">
          <img src="../../img/login/qq.png">
          <span>QQ</span>
        </div>
        <div  class="Weibo">
          <img src="../../img/login/weib.png">
          <span>微博</span>
        </div>
      </div>
  </section>
  </div>
</template>


<script>

</script>


<style>
.LoginWrap{
   width: 100%;
}
.LoginImgWrap{
  display: block;
  text-align: center;
  vertical-align: middle;
  width: 100%;
  line-height: 5.5rem;
}
.LoginImg img{
  width: 3.5rem;
  height: 1.2rem;
}
.ToLogin{
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-direction: column;
  font-size: 0.4rem;
  text-align: center;
  vertical-align: middle;

}
.Numlogin{

  padding-top: 0.3rem;
  position: relative;
  margin-bottom: 0.5rem;
  width: 90%;
  height:1.2rem;
  background-color: #b4282d;
  border-radius: 0.2rem;
  color: #ffffff;
}
.Numlogin span img{
  position: absolute;

}
.Maillogin{
  position: relative;
  padding-top: 0.3rem;
  width: 90%;
  border-radius: 0.2rem;
  height:1.2rem;
  border: solid 2px #b4282d;
  color: #b4282d;
}
  .Maillogin span img{
    position: absolute;

  }
  .QRej{
    padding-top: 0.4rem;

  }
  .LoginType{
    width: 100%;
    height: 1rem;
    display:flex;
    align-items: center;
    justify-content: center;
    padding-top: 3rem;
    line-height: 0.4rem;
    font-size: 0.4rem;

  }
.LoginType .Wechart,.Q, .Weibo {
  display:flex;
  align-items: center;
  justify-content: center;
  padding-right: 0.4rem;
  border-right: solid 2px #878787;

}
.Numlogin{
  position: relative;

}
.LoginPN{
  background-image: url("../../img/login/aa.png");
  background-repeat: no-repeat;
  position: absolute;
  width: 0.6rem;
  height:0.6rem;
  left: 2.6rem;
  overflow: hidden;
  background-position: 0rem -0.6rem;

}
.Maillogin{
  position: relative;
}
.LoginM{
  background-image: url("../../img/login/aa.png");
  background-repeat: no-repeat;
  position: absolute;
  width: 0.6rem;
  height:0.6rem;
  left: 2.6rem;
  background-position: 0rem 0rem;

}
  .Q{
    padding-left: 0.4rem;
    padding-right: 0.4rem;
  }
  .Weibo{
    padding-left: 0.4rem;
    border-right: none;

  }
</style>
