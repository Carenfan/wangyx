<template>
 <div class="HeaderWrap">
   <div class="nav-header">
     <header class="header">
       <a href="javascript:;" class="logo"></a>
       <div class="search">
         <i class="icon"></i>
         <span class="serach-content">搜索商品，共97565款好物</span>
       </div>
     </header>
     <div class="scroll">
       <div class="scroll-container ">
         <ul class="list">
           <li class="listItem  ">
             <a class="txt ">推荐</a>
           </li>
           <li class="listItem"  >
             <a class="txt  ">居家 </a>
           </li>
           <li class="listItem"  >
             <a class="txt :after">鞋包配饰 </a>
           </li>
           <li class="listItem  ">
             <a class="txt ">推荐</a>
           </li>
           <li class="listItem"  >
             <a class="txt  ">居家 </a>
           </li>
           <li class="listItem"  >
             <a class="txt :after">鞋包配饰 </a>
           </li>
           <li class="listItem"  >
             <a class="txt">服装 </a>
           </li>
           <li class="listItem"  >
             <a class="txt">电器 </a>
           </li>
         </ul>
       </div>
     </div>
   </div>
 </div>

</template>

<script>

</script>

<style>
 .nav-header{
    position: fixed;
    top:0;
    left: 0;
    width: 100%;
    height: 1.5rem;
    z-index: 10;
    background-color: #ffffff;
 }

 .header{
    padding:0.3rem ;
    display: flex;
    align-items: center;
  }
  .header .logo  {
    display: flex;
    background-image: url("./imgHeader/logo.png");
    width: 1.9rem;
    height: 0.6rem;
    margin-right: 0.3rem;
    background-position: center;
    background-size: 100% 100%;

  }
 .search{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 70%;
    height: 0.9rem;
    font-size: 0.4rem;
    background-color: #ededed;
    border-radius: 0.1rem;

  }
   .search .icon{
    display: flex;
    align-items: baseline;
    width: 0.3rem;
    height: 0.3rem;
    background-image: url("./imgHeader/search.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    margin-right: 0.2rem;
  }
  .serach-content{
    color: #000000;
    display: block;
  }

  .scroll-container{
    width: 100%;
    display: flex;
    overflow: hidden;
  }
 .list{
    width: 100%;
    float: left;
    display: inline-flex;
    /*display :flex;*/
    justify-content: space-around;
    flex-shrink: 0 ; /*!*文字不换行*!*/
    overflow: scroll;
    background-color: #ffffff;

  }
 .listItem {
    display: flex;
    justify-content: space-around;
    font-size: 0.4rem;
    padding-top: 0.1rem;
    padding-bottom: 0.1rem;

  }
 .listItem .txt{
    display: inline-block;
    position: relative;
    padding: 0 0.2rem;
    font-size: 0.4rem;
    width: 1.2rem;
    height: 0.4rem;
    text-align: center;
    background-color: #FFFFFF;
  }
   .listItem:active{
    color: #b4282d;
  }
   .listItem:first-child :after{
    position: absolute;
    content: "";
    left: 0;
    bottom: 0;
    height: 0.05rem;
    width: 90%;
    margin-left: 0.1rem;
    background-color: #b4282d;
  }



</style>
