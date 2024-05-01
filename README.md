# Divi-Blurb-module-slider-js
Divi Blurb module slider js
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.js"></script>
<script>
jQuery(document).ready(function() {
	jQuery('.divilife-3-col-feature-blurb-slider').slick({
    dots: false,
    slidesToShow: 4,
    slidesToScroll: 1,
    responsive: [
      {
        breakpoint: 980,
        settings: {
          slidesToShow: 2
        }
      },
      {
        breakpoint: 600,
        settings: {
          slidesToShow: 1
        }
      }
    ]
  }); 
});

  

</script>
<script>
jQuery(document).ready(function() {
jQuery(".pa-move-blurb-title").each(function () {
 var modhead = jQuery(this).find('.et_pb_module_header')
 var modimg = jQuery(this).find('.et_pb_main_blurb_image');
      jQuery(modhead).prependTo(modimg);
});
});
</script>
