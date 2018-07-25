<template>
  <div>
    <div class="swiper-container  " >
      <div class="swiper-wrapper  ">
        <div class="swiper-slide slideImg1">
          <img src="../../img/swImgSlide/1.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg2">
          <img src="../../img/swImgSlide/2.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg3">
          <img src="../../img/swImgSlide/3.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg4">
          <img src="../../img/swImgSlide/4.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg5">
          <img src="../../img/swImgSlide/5.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg6">
          <img src="../../img/swImgSlide/6.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg7">
          <img src="../../img/swImgSlide/7.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
        <div class="swiper-slide slideImg8">
          <img src="../../img/swImgSlide/8.jpg">
          <div class="SWTxt">
            <span>—严选推荐—</span>
            <span >海边度假必看攻略</span>
            <span>不去海边浪一浪，夏天算白过了</span>
          </div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>

  </div>

</template>

<script>
  import Swiper from 'swiper'
  import 'swiper/dist/css/swiper.min.css'
  export default {
    mounted(){
      this.$nextTick(()=> {
        new Swiper('.swiper-container', {
          slidesPerView: 'auto', /*swiper内容超出添加横向滚动条*/

//          autoplay:true,
          loop: true,
//          pagination: {
//            el: '.swiper-pagination',
//          },
        })
      })
    }
  }


</script>


<style>

  .swiper-container{
    width: 100%;
    margin-top: 2.2rem;
    background-color: #ffffff;
  }
  .swiper-container img{
    width: 100%;
    padding-left: 0.3rem;
  }
  .swiper-slide{
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-size: 0.4rem;
  }
  .SWTxt{
    background-color: #ffffff;
    position: absolute;
    width: 70%;
    height: 2.8rem;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    font-size: 0.4rem;
    line-height: 0.6rem;
    opacity: 0.8;

  }
  .SWTxt span:nth-child(2){
    font-size: 0.5rem;
    font-weight: bold;
  }
  .swiper-wrapper{
    width: 9rem;
    margin-left: 0.2rem;
    margin-right: 0.1rem;

  }

</style>
