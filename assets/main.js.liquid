jQuery(document).ready(function ($) {
    
    "use strict";
    
    
  $('.js-select').niceSelect(); // Input + -

  $('body').on('click', '.jq-number .minus', function (event) {
    var $input = $(this).parent().find('input');
    var count = parseInt($input.val()) - 1;
    count = count < 1 ? 1 : count;
    $input.val(count);
    $input.change();
    return false;
  });
    
     var $preloader = $('#page-preloader'),
    $spinner   = $preloader.find('.spinner-loader');
    $spinner.fadeOut();
    $preloader.delay(50).fadeOut('slow');
    
    
  $('body').on('click', '.jq-number .plus', function (event) {
    var $input = $(this).parent().find('input');
    $input.val(parseInt($input.val()) + 1);
    $input.change();
    return false;
  }); // Slider 

  const sliderFirstScreen = new Swiper('.slider-first-screen .swiper-container', {
    loop: true,
    speed: 4000,
    slidesPerView: 2,
    spaceBetween: 0,
    freeMode: true,
    observeParents: true,
    observer: true,
    autoplay: {
      delay: 0
    },
    breakpoints: {
      767: {
        slidesPerView: 3,
        spaceBetween: 0
      },
      959: {
        slidesPerView: 4,
        spaceBetween: 0
      }
    }
  });
  const sliderInfo = new Swiper('.slider-info .swiper-container', {
    loop: true,
    speed: 3000,
    slidesPerView: 1.8,
    spaceBetween: 20,
    freeMode: true,
    observeParents: true,
    observer: true,
    autoplay: {
      delay: 3000
    },
    pagination: {
      el: '.swiper-pagination',
      type: 'bullets',
      clickable: true
    }
  });

  function rargePrice() {
    var $range = $("#range-price");
    var $inputFrom = $("#range-price-from");
    var $inputTo = $("#range-price-to");
    var instance;
    var min = 0;
    var max = 5000;
    var from = 0;
    var to = 5000;
    $range.ionRangeSlider({
      skin: "round",
      type: "double",
      min: min,
      max: max,
      from: from,
      to: to,
      hide_min_max: true,
      hide_from_to: true,
      onStart: updateInputs,
      onChange: updateInputs,
      onFinish: updateInputs
    });
    instance = $range.data("ionRangeSlider");

    function updateInputs(data) {
      from = data.from;
      to = data.to;
      $inputFrom.prop("value", from);
      $inputTo.prop("value", to);
    }

    $inputFrom.on("change", function () {
      var val = $(this).prop("value"); // validate

      if (val < min) {
        val = min;
      } else if (val > to) {
        val = to;
      }

      instance.update({
        from: val
      });
      $(this).prop("value", val);
    });
    $inputTo.on("change", function () {
      var val = $(this).prop("value"); // validate

      if (val < from) {
        val = from;
      } else if (val > max) {
        val = max;
      }

      instance.update({
        to: val
      });
      $(this).prop("value", val);
    });
  }

  rargePrice();
  $(document).ready(function () {
    //E-mail Ajax Send
    $("form").submit(function () {
      //Change
      var th = $(this);
      $.ajax({
        type: "POST",
        url: "assets/mail/mail.php",
        //Change
        data: th.serialize()
      }).done(function () {
        UIkit.notification({
          message: 'Form sent successfully!',
          status: 'success',
          pos: 'top-center',
          timeout: 5000
        });
        setTimeout(function () {
          // Done Functions
          th.trigger("reset");
        }, 1000);
      });
      return false;
    });
  });
});
const animItems = document.querySelectorAll('._anim');

if (animItems.length > 0) {
  window.addEventListener('scroll', animOnSroll);

  function animOnSroll() {
    for (let index = 0; index < animItems.length; index++) {
      const animItem = animItems[index];
      const animItemHeight = animItem.offsetHeight;
      const animItemOffset = offset(animItem).top;
      const animStart = 4;
      let animItemPoint = window.innerHeight - animItemHeight / animStart;

      if (animItemHeight > window.innerHeight) {
        animItemPoint = window.innerHeight - window.innerHeight / animStart;
      }

      if (pageYOffset > animItemOffset - animItemPoint && pageYOffset < animItemOffset + animItemHeight) {
        animItem.classList.add('_active');
      } else {
        if (!animItem.classList.contains('_anim-no-repeat')) {
          animItem.classList.remove('_active');
        }
      }
    }
  }

  function offset(el) {
    const rect = el.getBoundingClientRect(),
          scrollLeft = window.pageXOffset || document.documentElement.scrollLeft,
          scrollTop = window.pageYOffset || document.documentElement.scrollTop;
    return {
      top: rect.top + scrollTop,
      left: rect.left + screenLeft
    };
  }

  setTimeout(() => {
    animOnSroll();
  }, 300);
}