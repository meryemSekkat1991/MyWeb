<template>
  <header class="header-one">
    <!-- Start top bar-->
    <div class="topbar-area fix hidden-xs">
      <div class="container">
        <div class="row">
          <div class="col-md-9 col-sm-9">
            <div class="topbar-left">
              <ul>
                <li><a href="#"><i class="fa fa-envelope"></i> info@MyWeb3.com</a></li>
                <li><a href="#"><i class="fa fa-phone-square"></i> +3234-7665545</a></li>
                <li><a href="#"><i class="fa fa-clock-o"></i> Mon - Fri: 10:00 - 18:00</a></li>
              </ul>
            </div>
          </div>
          <div class="col-md-3 col-sm-3">
            <div class="top-social">
              <ul>
                <li><a href="#"><i class="fa fa-skype"></i></a></li>
                <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                <li><a href="#"><i class="fa fa-facebook"></i></a></li>
                <li><a href="#"><i class="fa fa-google"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div><!-- End top bar-->
    <!-- header-area start-->
    <div class="header-area hidden-xs" id="sticker">
      <div class="container">
        <div class="row">
          <!-- logo start-->
          <div class="col-md-3 col-sm-3">
            <div class="logo">
              <!-- Brand-->
              <nuxt-link class="navbar-brand" to="/"><img src="/img/logo/logo2.png" alt="" /></nuxt-link>
            </div><!-- logo end-->
          </div>
          <div class="col-md-9 col-sm-9">
            <div class="header-right-link">
              <!-- search option end-->
              <nuxt-link class="s-menu" to="login">Get in Estimate</nuxt-link>
            </div><!-- mainmenu start-->
            <nav class="navbar navbar-default">
              <div class="collapse navbar-collapse" id="navbar-example">
                <div class="main-menu">
                  <ul class="nav navbar-nav navbar-right">
                    <li>
                      <nuxt-link class="pagess" to="#">Home</nuxt-link>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/">Home 01</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/index-2">Home 02</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/index-3">Home 03</nuxt-link>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <nuxt-link class="pagess" to="#">Pages</nuxt-link>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/about">About</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/team">team</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/faq">FAQ</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/review">Review</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/pricing">Pricing</nuxt-link>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <nuxt-link class="pagess" to="#">Services</nuxt-link>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/service">All services</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/service-details">Service-details</nuxt-link>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <nuxt-link class="pagess" to="#">Works</nuxt-link>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/project">Projects 01</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/project-2">Projects 02</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/project-details">Project details</nuxt-link>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <nuxt-link class="pagess" to="#">Blog</nuxt-link>
                      <ul class="sub-menu">
                        <li>
                          <nuxt-link to="/blog">Blog grid</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/blog-sidebar">Blog Sidebar</nuxt-link>
                        </li>
                        <li>
                          <nuxt-link to="/blog-details">Blog Details</nuxt-link>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <nuxt-link to="/contact">contacts</nuxt-link>
                    </li>
                  </ul>
                </div>
              </div>
            </nav><!-- mainmenu end-->
          </div>
        </div>
      </div>
    </div><!-- header-area end-->
    <!-- mobile-menu-area start-->
    <div class="mobile-menu-area hidden-lg hidden-md hidden-sm">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="mobile-menu">
              <div class="logo">
                <nuxt-link to="/"><img src="/img/logo/logo2.png" alt="" /></nuxt-link>
              </div>
              <nav id="dropdown">
                <ul>
                  <li>
                    <nuxt-link class="pagess" to="#">Home</nuxt-link>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/">Home 01</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/index-2">Home 02</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/index-3">Home 03</nuxt-link>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <nuxt-link class="pagess" to="#">Pages</nuxt-link>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/about">About</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/team">team</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/faq">FAQ</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/review">Review</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/pricing">Pricing</nuxt-link>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <nuxt-link class="pagess" to="#">Services</nuxt-link>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/service">All services</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/service-details">Service-details</nuxt-link>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <nuxt-link class="pagess" to="#">Works</nuxt-link>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/project">Projects 01</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/project-2">Projects 02</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/project-details">Project details</nuxt-link>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <nuxt-link class="pagess" to="#">Blog</nuxt-link>
                    <ul class="sub-menu">
                      <li>
                        <nuxt-link to="/blog">Blog grid</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/blog-sidebar">Blog Sidebar</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/blog-details">Blog Details</nuxt-link>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <nuxt-link to="/contact">contacts</nuxt-link>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
    export default {
        name: "Header",
      mounted() {

        (function ($) {
          "use strict";

        /*---------------------
         TOP Menu Stick
        --------------------- */

        var windows = $(window);
        var sticky = $('#sticker');

        windows.on('scroll', function() {
          var scroll = windows.scrollTop();
          if (scroll < 300) {
            sticky.removeClass('stick');
          }else{
            sticky.addClass('stick');
          }
        });




        /*----------------------------
         jQuery MeanMenu
        ------------------------------ */

        var mean_menu = $('nav#dropdown');
        mean_menu.meanmenu();

        /*---------------------
         wow .js
        --------------------- */
        function wowAnimation(){
          new WOW({
            offset: 100,
            mobile: true
          }).init()
        }
        wowAnimation()

        /*--------------------------
         scrollUp
        ---------------------------- */

        $.scrollUp({
          scrollText: '<i class="ti-arrow-up"></i>',
          easingType: 'linear',
          scrollSpeed: 900,
          animation: 'fade'
        });


        /*--------------------------
         collapse
        ---------------------------- */

        var panel_test = $('.panel-heading a');
        panel_test.on('click', function(){
          panel_test.removeClass('active');
          $(this).addClass('active');
        });
        })(jQuery);
      }
    }
</script>

<style scoped>

</style>
