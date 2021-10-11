<template>
  <!-- Start project Area -->
  <div class="project-area area-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-sm-12 col-xs-12 ">
          <div class="section-headline text-center">
            <h3>Our successful goal</h3>
            <p>Dummy text is also used to demonstrate the appearance of different typefaces and layouts</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="project-carousel">
          <!-- single-awesome-project start -->
          <div class="col-md-4 col-sm-4 col-xs-12">
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a href="#">
                  <img src="/img/project/1.jpg" alt="" />
                </a>
                <div class="add-actions text-center">
                  <a class="venobox" data-gall="myGallery" href="/img/project/1.jpg">
                    <i class="port-icon ti-zoom-in"></i>
                  </a>
                </div>
              </div>
              <div class="project-dec">
                <h4>Data collection</h4>
                <p>Our development opt in to the projects they genuinely want to work on, committing wholeheartedly to delivering.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 col-sm-4 col-xs-12">
            <!-- single-awesome-project start -->
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a href="#">
                  <img src="/img/project/2.jpg" alt="" />
                </a>
                <div class="add-actions text-center">
                  <a class="venobox" data-gall="myGallery" href="/img/project/2.jpg">
                    <i class="port-icon ti-zoom-in"></i>
                  </a>
                </div>
              </div>
              <div class="project-dec">
                <h4>Models development</h4>
                <p>Our development opt in to the projects they genuinely want to work on, committing wholeheartedly to delivering.</p>
              </div>
            </div>
            <!-- single-awesome-project end -->
          </div>
          <div class="col-md-4 col-sm-4 col-xs-12">
            <!-- single-awesome-project start -->
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a href="#">
                  <img src="/img/project/3.jpg" alt="" />
                </a>
                <div class="add-actions text-center">
                  <a class="venobox" data-gall="myGallery" href="img/project/3.jpg">
                    <i class="port-icon ti-zoom-in"></i>
                  </a>
                </div>
              </div>
              <div class="project-dec">
                <h4>Service deployment</h4>
                <p>Our development opt in to the projects they genuinely want to work on, committing wholeheartedly to delivering.</p>
              </div>
            </div>
            <!-- single-awesome-project end -->
          </div>
          <div class="col-md-4 col-sm-4 col-xs-12">
            <!-- single-awesome-project start -->
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a href="#">
                  <img src="/img/project/4.jpg" alt="" />
                </a>
                <div class="add-actions text-center">
                  <a class="venobox" data-gall="myGallery" href="/img/project/4.jpg">
                    <i class="port-icon ti-zoom-in"></i>
                  </a>
                </div>
              </div>
              <div class="project-dec">
                <h4>Environment project</h4>
                <p>Our development opt in to the projects they genuinely want to work on, committing wholeheartedly to delivering.</p>
              </div>
            </div>
            <!-- single-awesome-project end -->
          </div>
          <div class="col-md-4 col-sm-4 col-xs-12">
            <!-- single-awesome-project start -->
            <div class="single-awesome-project">
              <div class="awesome-img">
                <a href="#">
                  <img src="/img/project/5.jpg" alt="" />
                </a>
                <div class="add-actions text-center">
                  <a class="venobox" data-gall="myGallery" href="/img/project/5.jpg">
                    <i class="port-icon ti-zoom-in"></i>
                  </a>
                </div>
              </div>
              <div class="project-dec">
                <h4>Design solution</h4>
                <p>Our development opt in to the projects they genuinely want to work on, committing wholeheartedly to delivering.</p>
              </div>
            </div>
            <!-- single-awesome-project end -->
          </div>
        </div>
      </div>
    </div>
    <!-- End main content -->
  </div>
  <!-- End project Area -->
</template>

<script>
    export default {
        name: "Project",
      mounted() {
        (function ($) {
          "use strict";
        var Project_carousel = $('.project-carousel');
        Project_carousel.owlCarousel({
          loop:true,
          nav:true,
          autoplay:true,
          dots:false,
          navText: ["<i class='ti-angle-left'></i>","<i class='ti-angle-right'></i>"],
          responsive:{
            0:{
              items:1
            },
            700:{
              items:2
            },
            1000:{
              items:3
            }
          }
        });
        })(jQuery);
      }
    }
</script>

<style scoped>

</style>
