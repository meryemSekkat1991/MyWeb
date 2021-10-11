<template lang="pug">
  header.header-one
    // Start top bar
    .topbar-area.fix.hidden-xs
      .container
        .row
          .col-md-9.col-sm-9
            .topbar-left
              ul
                li
                  a(href='#')
                    i.fa.fa-envelope
                    |  info@MyWeb3.com
                li
                  a(href='#')
                    i.fa.fa-phone-square
                    |  +3234-7665545
                li
                  a(href='#')
                    i.fa.fa-clock-o
                    |  Mon - Fri: 10:00 - 18:00
          .col-md-3.col-sm-3
            .top-social
              ul
                li
                  a(href='#')
                    i.fa.fa-skype
                li
                  a(href='#')
                    i.fa.fa-twitter
                li
                  a(href='#')
                    i.fa.fa-facebook
                li
                  a(href='#')
                    i.fa.fa-google
    // End top bar
    // header-area start
    #sticker.header-area.hidden-xs
      .container
        .row
          // logo start
          .col-md-3.col-sm-3
            .logo
              // Brand
              nuxt-link.navbar-brand(to='/')
                img(src='/img/logo/logo2.png' alt='')
            // logo end
          .col-md-9.col-sm-9
            .header-right-link
              // search option end
              nuxt-link.s-menu(to='login') Get in Estimate
            // mainmenu start
            nav.navbar.navbar-default
              #navbar-example.collapse.navbar-collapse
                .main-menu
                  ul.nav.navbar-nav.navbar-right
                    li
                      nuxt-link.pagess(to='#') Home
                      ul.sub-menu
                        li
                          nuxt-link(to='/') Home 01
                        li
                          nuxt-link(to='/index-2') Home 02
                        li
                          nuxt-link(to='/index-3') Home 03
                    li
                      nuxt-link.pagess(to='#') Pages
                      ul.sub-menu
                        li
                          nuxt-link(to='/about') About
                        li
                          nuxt-link(to='/team') team
                        li
                          nuxt-link(to='/faq') FAQ
                        li
                          nuxt-link(to='/review') Review
                        li
                          nuxt-link(to='/pricing') Pricing
                    li
                      nuxt-link.pagess(to='#') Services
                      ul.sub-menu
                        li
                          nuxt-link(to='/service') All services
                        li
                          nuxt-link(to='/service-details') Service-details
                    li
                      nuxt-link.pagess(to='#') Works
                      ul.sub-menu
                        li
                          nuxt-link(to='/project') Projects 01
                        li
                          nuxt-link(to='/project-2') Projects 02
                        li
                          nuxt-link(to='/project-details') Project details
                    li
                      nuxt-link.pagess(to='#') Blog
                      ul.sub-menu
                        li
                          nuxt-link(to='/blog') Blog grid
                        li
                          nuxt-link(to='/blog-sidebar') Blog Sidebar
                        li
                          nuxt-link(to='/blog-details') Blog Details
                    li
                      nuxt-link(to='/contact') contacts
            // mainmenu end
    // header-area end
    // mobile-menu-area start
    .mobile-menu-area.hidden-lg.hidden-md.hidden-sm
      .container
        .row
          .col-md-12
            .mobile-menu
              .logo
                nuxt-link(to='/')
                  img(src='/img/logo/logo2.png' alt='')
              nav#dropdown
                ul
                  li
                    nuxt-link.pagess(to='#') Home
                    ul.sub-menu
                      li
                        nuxt-link(to='/') Home 01
                      li
                        nuxt-link(to='/index-2') Home 02
                      li
                        nuxt-link(to='/index-3') Home 03
                  li
                    nuxt-link.pagess(to='#') Pages
                    ul.sub-menu
                      li
                        nuxt-link(to='/about') About
                      li
                        nuxt-link(to='/team') team
                      li
                        nuxt-link(to='/faq') FAQ
                      li
                        nuxt-link(to='/review') Review
                      li
                        nuxt-link(to='/pricing') Pricing
                  li
                    nuxt-link.pagess(to='#') Services
                    ul.sub-menu
                      li
                        nuxt-link(to='/service') All services
                      li
                        nuxt-link(to='/service-details') Service-details
                  li
                    nuxt-link.pagess(to='#') Works
                    ul.sub-menu
                      li
                        nuxt-link(to='/project') Projects 01
                      li
                        nuxt-link(to='/project-2') Projects 02
                      li
                        nuxt-link(to='/project-details') Project details
                  li
                    nuxt-link.pagess(to='#') Blog
                    ul.sub-menu
                      li
                        nuxt-link(to='/blog') Blog grid
                      li
                        nuxt-link(to='/blog-sidebar') Blog Sidebar
                      li
                        nuxt-link(to='/blog-details') Blog Details
                  li
                    nuxt-link(to='/contact') contacts
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
