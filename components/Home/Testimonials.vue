<template>
  <!-- Start testimonials Area -->
  <div class="reviews-area bg-color fix area-padding">
    <div class="container">
      <div class="row">
        <div class="reviews-top">
          <div class="col-md-5 col-sm-5 col-xs-12">
            <div class="testimonial-inner">
              <div class="review-head">
                <h3>Our customer say <span class="color"> about our company</span> work</h3>
                <p>The phrasal sequence of the Lorem Ipsum text is now so widespread and commonplace that many DTP programmes can generate dummy. The phrasal sequence of the Lorem Ipsum text is now so widespread and commonplace that many DTP programmes can generate dummy</p>
                <nuxt-link class="reviews-btn" to="review">More reviews</nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-md-7 col-sm-7 col-xs-12">
            <div class="reviews-content">
              <!-- start testimonial carousel -->
              <div class="testimonial-carousel item-indicator">
                <div class="single-testi">
                  <div class="testi-text">
                    <div class="clients-text">
                      <div class="client-rating">
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                      </div>
                      <p>When replacing a multi-lined selection of text, the generated dummy text maintains the amount of lines. When replacing a selection. help agencies.</p>
                    </div>
                    <div class="testi-img ">
                      <img src="/img/review/1.jpg" alt="">
                      <div class="guest-details">
                        <h4>Hamilton</h4>
                        <span class="guest-rev">Clients - <a href="#">General customer</a></span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- End single item -->
                <div class="single-testi">
                  <div class="testi-text">
                    <div class="clients-text">
                      <div class="client-rating">
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                      </div>
                      <p>When replacing a multi-lined selection of text, the generated dummy text maintains the amount of lines. When replacing a selection. help agencies.</p>
                    </div>
                    <div class="testi-img ">
                      <img src="/img/review/2.jpg" alt="">
                      <div class="guest-details">
                        <h4>Angel lima</h4>
                        <span class="guest-rev">Clients - <a href="#">General customer</a></span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- End single item -->
                <div class="single-testi">
                  <div class="testi-text">
                    <div class="clients-text">
                      <div class="client-rating">
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                      </div>
                      <p>When replacing a multi-lined selection of text, the generated dummy text maintains the amount of lines. When replacing a selection. help agencies.</p>
                    </div>
                    <div class="testi-img ">
                      <img src="/img/review/3.jpg" alt="">
                      <div class="guest-details">
                        <h4>Arthur Doil</h4>
                        <span class="guest-rev">Clients - <a href="#">General customer</a></span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- End single item -->
                <div class="single-testi">
                  <div class="testi-text">
                    <div class="clients-text">
                      <div class="client-rating">
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                        <a href="#"><i class="ti-star"></i></a>
                      </div>
                      <p>When replacing a multi-lined selection of text, the generated dummy text maintains the amount of lines. When replacing a selection. help agencies.</p>
                    </div>
                    <div class="testi-img ">
                      <img src="/img/review/4.jpg" alt="">
                      <div class="guest-details">
                        <h4>Gabriel Hank</h4>
                        <span class="guest-rev">Clients - <a href="#">General customer</a></span>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- End single item -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End testimonials end -->
</template>

<script>
    export default {
        name: "Testimonials",
      mounted() {
        (function ($) {
          "use strict";
        var review = $('.testimonial-carousel');
        review.owlCarousel({
          loop:true,
          nav:false,
          margin:30,
          center:true,
          dots:true,
          autoplay:true,
          responsive:{
            0:{
              items:1
            },
            768:{
              items:1
            },
            1000:{
              items:2
            }
          }
        });
        })(jQuery);
      }
    }
</script>

<style scoped>

</style>
