<template>
  <div>
    <nuxt />
  </div>
</template>

<script>
  export default {
    components: {

    },
    head(){
      return {
        title: "MyWeb - Vue Nuxt Data Science & AI Template "
      }
    },
    mounted () {

        /*--------------------------
         MagnificPopup
        ---------------------------- */

      $('.video-play').magnificPopup({
        type: 'iframe'
      })


            /*--------------------------
       preloader
      ---------------------------- */

      $(window).on('load',function(){
        var pre_loader = $('#preloader')
        pre_loader.fadeOut('slow',function(){$(this).remove();});
      });

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

            /*---------------------
        venobox
      --------------------- */
      var veno_box = $('.venobox');
      veno_box.venobox();
    }
  }
</script>

<style>

</style>
