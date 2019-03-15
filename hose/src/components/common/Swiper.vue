<template>
    <div>
      <div class="swiper">
        <mt-swipe :show-indicators="false">
        <mt-swipe-item><img src="../../assets/logo.png" alt=""></mt-swipe-item>
        <mt-swipe-item>2</mt-swipe-item>
        <mt-swipe-item>3</mt-swipe-item>
      </mt-swipe>
      </div>
    </div>
</template>

<script>
    export default {
        name: "Swiper",
        data : function(){
          return {
            
          }
        },
        
    }
</script>

<style scoped>
  .swiper{
    height:220px;
  }
  .swiper img{
    width:100%;
    height:100%;
    display: block;
  }
</style>
