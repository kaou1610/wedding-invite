<template>
  <div id="app">
    
    <!-- Navbar Start -->
    <nav class="navbar fixed-top shadow-sm navbar-expand-lg bg-dark navbar-dark py-3 py-lg-0 px-lg-5">
        <a href="index.html" class="navbar-brand d-block d-lg-none">
            <h1 class="font-secondary text-white mb-n2">Nam <span class="text-primary">&</span> Phương</h1>
        </a>
        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
            <div class="navbar-nav ml-auto py-0">
                <a href="#home" class="nav-item nav-link active">Home</a>
                <a href="#about" class="nav-item nav-link">Invite</a>
                <!-- <a href="#story" class="nav-item nav-link">Story</a> -->
                <a href="#gallery" class="nav-item nav-link">Pre-wed</a>
            </div>
            <a href="index.html" class="navbar-brand mx-5 d-none d-lg-block">
                <h1 class="font-secondary text-white mb-n2">Nam <span class="text-primary">&</span> Phương</h1>
            </a>
            <div class="navbar-nav mr-auto py-0">
                <!-- <a href="#family" class="nav-item nav-link">Family</a> -->
                <a href="#event" class="nav-item nav-link">Event</a>
                <a href="#rsvp" class="nav-item nav-link">RSVP</a>
                <a href="#contact" class="nav-item nav-link">Contact</a>
            </div>
        </div>
    </nav>
    <!-- Navbar End -->


    <!-- Carousel Start -->
    <div class="container-fluid p-0 mb-5 pb-5" id="home">
        <div id="header-carousel" class="carousel slide carousel-fade" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item position-relative active" style="height: 100vh; min-height: 400px;">
                    <img class="position-absolute w-100 h-100" src="./img/carousel1.jpg" style="object-fit: cover;">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h1 class="display-1 font-secondary text-white mt-n3 mb-md-4">Nam & Phương</h1>
                            <div class="d-inline-block border-top border-bottom border-light py-3 px-4">
                                <h3 class="text-uppercase font-weight-normal text-white m-0" style="letter-spacing: 2px;">We're getting married</h3>
                            </div>
                            <!-- <button type="button" class="btn-play mx-auto" data-toggle="modal"
                                data-src="https://www.youtube.com/embed/DWRcNpR6Kdc" data-target="#videoModal">
                                <span></span>
                            </button> -->
                        </div>
                    </div>
                </div>
                <div class="carousel-item position-relative" style="height: 100vh; min-height: 400px;">
                    <img class="position-absolute w-100 h-100" src="./img/5Q6A7474.jpg" style="object-fit: cover;">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h1 class="display-1 font-secondary text-white mt-n3 mb-md-4">Nam & Phương</h1>
                            <div class="d-inline-block border-top border-bottom border-light py-3 px-4">
                                <h3 class="text-uppercase font-weight-normal text-white m-0" style="letter-spacing: 2px;">We're getting married</h3>
                            </div>
                            <!-- <button type="button" class="btn-play mx-auto" data-toggle="modal"
                                data-src="https://www.youtube.com/embed/DWRcNpR6Kdc" data-target="#videoModal">
                                <span></span>
                            </button> -->
                        </div>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev justify-content-start" href="#header-carousel" data-slide="prev">
                <div class="btn btn-primary px-0" style="width: 68px; height: 68px;">
                    <span class="carousel-control-prev-icon mt-3"></span>
                </div>
            </a>
            <a class="carousel-control-next justify-content-end" href="#header-carousel" data-slide="next">
                <div class="btn btn-primary px-0" style="width: 68px; height: 68px;">
                    <span class="carousel-control-next-icon mt-3"></span>
                </div>
            </a>
        </div>
    </div>
    <!-- Carousel End -->


    <!-- Video Modal Start -->
    <div class="modal fade" id="videoModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-body">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>        
                    <!-- 16:9 aspect ratio -->

                </div>
            </div>
        </div>
    </div>
    <!-- Video Modal End -->


    <!-- About Start -->
    <div class="container-fluid py-5" id="about">
        <div class="container py-5">
            <div class="section-title position-relative text-center">
                <!-- <h6 class="text-uppercase text-primary mb-3" style="letter-spacing: 3px;">About</h6> -->
                <h6 class="text-uppercase text-primary mb-3" style="letter-spacing: 3px;">Invitation</h6>
                <h1 class="font-secondary display-4">Thế Nam & Minh Phương</h1>
                <i class="far fa-heart text-dark"></i>
            </div>
            <div class="position-relative text-center">
                <h2 class="font-secondary">Trân trọng kính mời bạn và người thương</h2>
                <h2 class="font-secondary">Tới dự bữa cơm thân mật chung vui cùng gia đình</h2>
            </div>
            <div class="row m-0 mb-4 mb-md-0 pb-2 pb-md-0 pt-3">
                <div class="col-md-6 p-0 text-center text-md-left">
                    <div class="h-100 d-flex flex-column justify-content-center bg-pink p-5 text-dark">
                        <h3 class="mb-3 text-light">Nhà trai</h3>
                        <p> 14 giờ 00 phút, thứ hai ngày 29 tháng 5 năm 2023</p>
                        <p> Thôn Thụy Hà, xã Bắc Hồng, huyện Đông Anh, thành phố Hà Nội </p>
                        <h3 class="font-secondary font-weight-normal text-light mb-3"><font-awesome-icon icon="fa-solid fa-person" />Chú rể: Nguyễn Thế Nam</h3>
                        <p>Bố: Nguyễn Thế Thuấn</p>
                        <p>Mẹ: Nguyễn Thị Hương</p>
                        <div class="position-relative">
                            <a title="Go to google maps" class="btn btn-outline-primary btn-square mr-1" href="https://www.google.com/maps/place/Nh%C3%A0+V%C4%83n+Ho%C3%A1+Th%C3%B4n+Thu%E1%BB%B5+H%C3%A0/@21.1840598,105.7990128,18.5z/data=!4m15!1m8!3m7!1s0x313501edda8c8083:0x736404d34c4f71a4!2zxJAuIEzDoG5nIFRo4buleSBIw6AsIFRo4buleSBIw6AsIELhuq9jIEjhu5NuZywgxJDDtG5nIEFuaCwgSMOgIE7hu5lpLCBWaeG7h3QgTmFt!3b1!8m2!3d21.1835548!4d105.8023962!16s%2Fg%2F11fj966qs4!3m5!1s0x313501ee759f96fb:0x73c209343e8e6d7f!8m2!3d21.1845346!4d105.7995901!16s%2Fg%2F11b807csp2"><i class="fas fa-map-marker-alt"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 p-0" style="min-height: 400px;">
                    <img class="position-absolute w-100 h-100" src="./img/about1.png" style="object-fit: cover;">
                </div>
            </div>
            <div class="row m-0">
                <div class="col-md-6 p-0" style="min-height: 400px;">
                    <img class="position-absolute w-100 h-100" src="./img/about2.png" style="object-fit: cover;">
                </div>
                <div class="col-md-6 p-0 text-center text-md-left">
                    <div class="h-100 d-flex flex-column justify-content-center bg-pink p-5 text-dark">
                        <h3 class="mb-3 text-light">Nhà gái</h3>
                        <p> 10 giờ 00 phút, thứ hai ngày 29 tháng 5 năm 2023</p>
                        <p> Thôn Phan Xá, xã Hồng Phong, huyện Vũ Thư, tỉnh Thái Bình </p>
                        <h3 class="font-secondary font-weight-normal text-light  mb-3"><i class="fa fa-female pr-3"></i>Cô dâu: Vũ Thị Minh Phương</h3>
                        <p>Bố: Vũ Lương Bằng</p>
                        <p>Mẹ: Bùi Minh Nguyệt</p>                        
                        <div class="position-relative">
                            <a title="Go to google maps" class="btn btn-outline-primary btn-square mr-1" href="https://www.google.com/maps/place/20%C2%B021'03.9%22N+106%C2%B016'02.5%22E/@20.3512573,106.266981,133m/data=!3m1!1e3!4m13!1m8!3m7!1s0x3135e23d7ba750cf:0x660464352edb041d!2zSOG7k25nIFBob25nLCBWxakgVGjGsCwgVGjDoWkgQsOsbmgsIFZp4buHdCBOYW0!3b1!8m2!3d20.3398181!4d106.2669247!16s%2Fg%2F1tmxnhd9!3m3!8m2!3d20.351095!4d106.267364"><i class="fas fa-map-marker-alt"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- About End -->


    <!-- Gallery Start -->
    <div class="container-fluid bg-gallery" id="gallery" style="padding: 120px 0; margin: 90px 0;">
        <div class="section-title position-relative text-center" style="margin-bottom: 120px;">
            <h6 class="text-uppercase text-primary mb-3" style="letter-spacing: 3px;">Pre-Wedding</h6>
            <h1 class="font-secondary display-4 text-white">Our Photo Pre-Wedding</h1>
            <i class="far fa-heart text-white"></i>
        </div>
        <div class="owl-carousel gallery-carousel">
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre1.jpg" alt="">
                <a href="./img/pre1.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre4.jpg" alt="">
                <a href="./img/pre4.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre3.jpg" alt="">
                <a href="./img/pre3.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre2.jpg" alt="">
                <a href="./img/pre2.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre05.jpg" alt="">
                <a href="./img/pre05.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
            <div class="gallery-item">
                <img class="img-fluid w-100" src="./img/pre6.jpg" alt="">
                <a href="./img/pre6.jpg" data-lightbox="gallery">
                    <i class="fa fa-2x fa-plus text-white"></i>
                </a>
            </div>
        </div>
    </div>
    <!-- Gallery End -->


    <!-- Event Start -->
    <div class="container-fluid py-5" id="event">
        <div class="container py-5">
            <div class="section-title position-relative text-center">
                <h6 class="text-uppercase text-primary mb-3" style="letter-spacing: 3px;">Event</h6>
                <h1 class="font-secondary display-4">Our Wedding Event</h1>
                <i class="far fa-heart text-dark"></i>
            </div>
            <div class="row justify-content-center">
                <div class="col-md-6 text-center">
                    <h5 class="font-weight-normal text-muted mb-3 pb-3">Trân trọng kính mời bạn và người thương</h5>
                    <h5 class="font-weight-normal text-muted mb-3 pb-3">Tới dự lễ thành hôn của chúng tôi</h5>
                    <!-- <h5 class="font-weight-normal text-muted mb-3 pb-3">Tổ chức tại</h5> -->
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 border-right border-primary">
                    <div class="text-center text-md-right mr-md-3 mb-4 mb-md-0">
                        <img class="img-fluid mb-4" src="./img/event1.jpg" alt="">
                        <h4 class="mb-3">Nhà trai</h4>
                        <p class="mb-2">Thôn Thụy Hà, xã Bắc Hồng, huyện Đông Anh, thành phố Hà Nội</p>
                        <p class="mb-0">14: 00, thứ hai ngày 29 tháng 5 năm 2023</p>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="text-center text-md-left ml-md-3">
                        <img class="img-fluid mb-4" src="./img/event02.jpg" alt="">
                        <h4 class="mb-3">Nhà gái</h4>
                        <p class="mb-2">Thôn Phan Xá, xã Hồng Phong, huyện Vũ Thư, tỉnh Thái Bình</p>
                        <p class="mb-0">10: 00, thứ hai ngày 29 tháng 5 năm 2023</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Event End -->


    <!-- RSVP Start -->
    <div class="container-fluid py-5" id="rsvp">
        <div class="container py-5">
            <div class="section-title position-relative text-center">
                <h6 class="text-uppercase text-primary mb-3" style="letter-spacing: 3px;">RSVP</h6>
                <h1 class="font-secondary display-4">Join Our Party</h1>
                <i class="far fa-heart text-dark"></i>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="text-center">
                        <form>
                            <div class="form-row">
                                <div class="form-group col-sm-6">
                                    <input type="text" class="form-control bg-secondary border-0 py-4 px-3" placeholder="Your Name"/>
                                </div>
                                <div class="form-group col-sm-6">
                                    <input type="email" class="form-control bg-secondary border-0 py-4 px-3" placeholder="Your Email"/>
                                </div>
                            </div>
                            <div class="form-row">
                                <div class="form-group col-sm-6">
                                    <select class="form-control bg-secondary border-0" style="height: 52px;">
                                        <option>Number of Guest</option>
                                        <option>1</option>
                                        <option>2</option>
                                        <option>3</option>
                                        <option>4</option>
                                    </select>
                                </div>
                                <div class="form-group col-sm-6">
                                    <select class="form-control bg-secondary border-0" style="height: 52px;">
                                        <option>I'm Attending</option>
                                        <option>All Events</option>
                                        <option>Wedding Party</option>
                                    </select>
                                </div>
                            </div>
                            <div class="form-group">
                                <textarea class="form-control bg-secondary border-0 py-2 px-3" rows="5" placeholder="Message" required="required"></textarea>
                            </div>
                            <div>
                                <button class="btn btn-primary font-weight-bold py-3 px-5" type="submit">Submit</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- RSVP End -->


    <!-- Footer Start -->
    <div class="container-fluid bg-dark text-white py-5" id="contact" style="margin-top: 90px;">
        <div class="container text-center py-5">
            <div class="section-title position-relative text-center">
                <h1 class="font-secondary display-3 text-white">Thank You</h1>
                <i class="far fa-heart text-white"></i>
            </div>
            <div class="d-flex justify-content-center mb-4">
                <a class="btn btn-lg btn-outline-light btn-lg-square mr-2" href="#"><i class="fab fa-twitter"></i></a>
                <a class="btn btn-lg btn-outline-light btn-lg-square mr-2" href="#"><i class="fab fa-facebook-f"></i></a>
                <a class="btn btn-lg btn-outline-light btn-lg-square mr-2" href="#"><i class="fab fa-linkedin-in"></i></a>
                <a class="btn btn-lg btn-outline-light btn-lg-square" href="#"><i class="fab fa-instagram"></i></a>
            </div>
            <div class="d-flex justify-content-center py-2">
                <p class="text-white" href="#">info@example.com</p>
                <span class="px-3">|</span>
                <p class="text-white" href="#">+012 345 6789</p>
            </div>
            <p class="m-0">&copy; <a class="text-primary" href="#">Domain Name</a>. Designed by <a class="text-primary" href="https://htmlcodex.com">HTML Codex</a>
            </p>
        </div>
    </div>
    <!-- Footer End -->


    <!-- Scroll to Bottom -->
    <i class="fa fa-2x fa-angle-down text-white scroll-to-bottom"></i>

    <!-- Back to Top -->
    <a href="#" class="btn btn-lg btn-outline-primary btn-lg-square back-to-top"><i class="fa fa-angle-double-up"></i></a>

  </div>
</template>

<script>
import $ from "jquery";

export default {
  name: "App",
  components: {
    // HelloWorld,
  },
  ready () {

    $(document).ready(function ($) {
      "use strict";

    // Navbar on scrolling
    $(window).scroll(function () {
        if ($(this).scrollTop() > 200) {
            $('.navbar').fadeIn('slow').css('display', 'flex');
        } else {
            $('.navbar').fadeOut('slow').css('display', 'none');
        }
    });


    // Smooth scrolling on the navbar links
    $(".navbar-nav a").on('click', function (event) {
        if (this.hash !== "") {
            event.preventDefault();
            
            $('html, body').animate({
                scrollTop: $(this.hash).offset().top - 45
            }, 1500, 'easeInOutExpo');
            
            if ($(this).parents('.navbar-nav').length) {
                $('.navbar-nav .active').removeClass('active');
                $(this).closest('a').addClass('active');
            }
        }
    });


    // Modal Video
    $(document).ready(function () {
        var $videoSrc;
        $('.btn-play').click(function () {
            $videoSrc = $(this).data("src");
        });
        console.log($videoSrc);

        $('#videoModal').on('shown.bs.modal', function () {
            $("#video").attr('src', $videoSrc + "?autoplay=1&amp;modestbranding=1&amp;showinfo=0");
        })

        $('#videoModal').on('hide.bs.modal', function () {
            $("#video").attr('src', $videoSrc);
        })
    });


    // Scroll to Bottom
    $(window).scroll(function () {
        if ($(this).scrollTop() > 100) {
            $('.scroll-to-bottom').fadeOut('slow');
        } else {
            $('.scroll-to-bottom').fadeIn('slow');
        }
    });


    // Portfolio isotope and filter
    var portfolioIsotope = $('.portfolio-container').isotope({
        itemSelector: '.portfolio-item',
        layoutMode: 'fitRows'
    });
    $('#portfolio-flters li').on('click', function () {
        $("#portfolio-flters li").removeClass('active');
        $(this).addClass('active');

        portfolioIsotope.isotope({filter: $(this).data('filter')});
    });
    
    
    // Back to top button
    $(window).scroll(function () {
        if ($(this).scrollTop() > 200) {
            $('.back-to-top').fadeIn('slow');
        } else {
            $('.back-to-top').fadeOut('slow');
        }
    });
    $('.back-to-top').click(function () {
        $('html, body').animate({scrollTop: 0}, 1500, 'easeInOutExpo');
        return false;
    });


    // Gallery carousel
    $(".gallery-carousel").owlCarousel({
        autoplay: false,
        smartSpeed: 1500,
        dots: false,
        loop: true,
        nav : true,
        navText : [
            '<i class="fa fa-angle-left" aria-hidden="true"></i>',
            '<i class="fa fa-angle-right" aria-hidden="true"></i>'
        ],
        responsive: {
            0:{
                items:1
            },
            576:{
                items:2
            },
            768:{
                items:3
            },
            992:{
                items:4
            },
            1200:{
                items:5
            }
        }
    });
    })
  },
};
</script>

<style>
.bg-gallery {
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../src/img/pre.jpg), no-repeat center center;
  background-size: cover;
}

</style>