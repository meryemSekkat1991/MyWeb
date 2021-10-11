<template>
  <div id="preloader"></div>
</template>

<script>
    export default {
        name: "Preloader",
      mounted() {
        (function ($) {
          "use strict";
          $(window).on('load',function(){
            var pre_loader = $('#preloader')
            pre_loader.fadeOut('slow',function(){$(this).remove();});
          });
        })(jQuery);
    }
    }
</script>

<style scoped>

</style>
