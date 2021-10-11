<template>
  <!-- Start Brand Area -->
  <div class="brand-area bg-color">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12">
          <div class="brand-content">
            <div class="brand-items brand-carousel">
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/1.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/2.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/3.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/4.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/5.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/6.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/1.png" alt=""></a>
              </div>
              <div class="single-brand-item">
                <a href="#"><img src="/img/brand/2.png" alt=""></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Banner Area -->
</template>

<script>
    export default {
        name: "Brand",
      mounted() {
        var brand = $('.brand-carousel');
        brand.owlCarousel({
          loop:true,
          nav:false,
          margin:50,
          dots:true,
          autoplay:true,
          responsive:{
            0:{
              items:1
            },
            768:{
              items:4
            },
            1000:{
              items:6
            }
          }
        });
      }
    }
</script>

<style scoped>

</style>
