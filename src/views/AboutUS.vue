<template>
  <Header></Header>
  <section class="about-section">
    <div class="container">
      <div class="row">
        <div class="content-column col-lg-6 col-md-12 col-sm-12 order-2">
          <div class="inner-column">
            <div class="sec-title">
              <span class="title">About Leftover Closet began</span>
              <h2>The Leftover Closet began its journey in 2021</h2>
            </div>
            <div class="text">
              The Leftover Closet began its journey in 2021 with a clear mission
              in mind: to offer customers access to branded products at
              affordable prices. To achieve this, we devised a unique concept
              where we source branded, 100% original clothing from overseas and
              make it available to our customers. The distinguishing feature of
              our offerings is that they are not used, pre-loved, or thrifted
              items; they are, in fact, entirely new garments. However, it's
              important to note that the designs may be slightly dated, ranging
              from a minimum of 6 months to 2 years old.
            </div>
            <div class="text">
              Upon receiving our products, our team of highly skilled clothing
              professionals rigorously inspects each item. In fact, each product
              undergoes a thorough examination by four different workers to
              ensure its quality and authenticity. Subsequently, our products
              are meticulously dry cleaned, ensuring that when they reach our
              customers, they are in pristine, ready-to-wear condition.
            </div>
            <div class="btn-box">
              <a href="#" class="theme-btn btn-style-one">Contact Us</a>
            </div>
          </div>
        </div>

        <!-- Image Column -->
        <div class="image-column col-lg-6 col-md-12 col-sm-12">
          <div class="inner-column wow fadeInLeft">
            <!-- <div class="author-desc">
                <h2>Rahul Kumar Yadav</h2>
                <span>Web Developer</span>
              </div> -->
            <figure class="image-1">
              <a href="#" class="lightbox-image" data-fancybox="images"
                ><img
                  title="Rahul Kumar Yadav"
                  src="https://i.ibb.co/QP6Nmpf/image-1-about.jpg"
                  alt=""
              /></a>
            </figure>
          </div>
        </div>
      </div>
      <div class="sec-title">
        <span class="title">Our Future Goal</span>
        <h2>We want to lead in innovation & Technology</h2>
      </div>
      <div class="text">
        Before dispatching any product to a customer, we subject it to yet
        another round of scrutiny by our professionals. This double-checking
        process ensures that our customers receive nothing short of the best.
      </div>
      <div class="text">
        It's worth noting that while our products may be priced slightly higher
        than thrifted or used items, they are still more affordable than
        brand-new, current-season pieces. Our commitment to offering quality,
        original branded clothing at reasonable prices remains unwavering, and
        our products are thoughtfully handpicked with the customers' budget in
        mind. We take pride in our unique approach, as we believe it allows
        individuals to access high-quality fashion without breaking the bank.
      </div>
    </div>
  </section>
</template>
<script>
import Header from "../components/HeaderComp.vue";
export default {
  components: {
    Header,
  },
};
</script>

<style>
h1,
h2,
h3,
h4,
h5,
h6 {
}
a,
a:hover,
a:focus,
a:active {
  text-decoration: none;
  outline: none;
}

a,
a:active,
a:focus {
  color: #6f6f6f;
  text-decoration: none;
  transition-timing-function: ease-in-out;
  -ms-transition-timing-function: ease-in-out;
  -moz-transition-timing-function: ease-in-out;
  -webkit-transition-timing-function: ease-in-out;
  -o-transition-timing-function: ease-in-out;
  transition-duration: 0.2s;
  -ms-transition-duration: 0.2s;
  -moz-transition-duration: 0.2s;
  -webkit-transition-duration: 0.2s;
  -o-transition-duration: 0.2s;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
img {
  max-width: 100%;
  height: auto;
}
section {
  padding: 60px 0;
  /* min-height: 100vh;*/
}

.sec-title {
  position: relative;
  z-index: 1;
  margin-bottom: 60px;
}

.sec-title .title {
  position: relative;
  display: block;
  font-size: 18px;
  line-height: 24px;
  color: #00aeef;
  font-weight: 500;
  margin-bottom: 15px;
}

.sec-title h2 {
  position: relative;
  display: block;
  font-size: 40px;
  line-height: 1.28em;
  color: #222222;
  font-weight: 600;
  padding-bottom: 18px;
}

.sec-title h2:before {
  position: absolute;
  content: "";
  left: 0px;
  bottom: 0px;
  width: 50px;
  height: 3px;
  background-color: #d1d2d6;
}

.sec-title .text {
  position: relative;
  font-size: 16px;
  line-height: 26px;
  color: #848484;
  font-weight: 400;
  margin-top: 35px;
}

.sec-title.light h2 {
  color: #ffffff;
}

.sec-title.text-center h2:before {
  left: 50%;
  margin-left: -25px;
}

.list-style-one {
  position: relative;
}

.list-style-one li {
  position: relative;
  font-size: 16px;
  line-height: 26px;
  color: #222222;
  font-weight: 400;
  padding-left: 35px;
  margin-bottom: 12px;
}

.list-style-one li:before {
  content: "\f058";
  position: absolute;
  left: 0;
  top: 0px;
  display: block;
  font-size: 18px;
  padding: 0px;
  color: #ff2222;
  font-weight: 600;
  -moz-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  font-style: normal;
  font-variant: normal;
  text-rendering: auto;
  line-height: 1.6;
  font-family: "Font Awesome 5 Free";
}

.list-style-one li a:hover {
  color: #44bce2;
}

.btn-style-one {
  position: relative;
  display: inline-block;
  font-size: 17px;
  line-height: 30px;
  color: #ffffff;
  padding: 10px 30px;
  font-weight: 600;
  overflow: hidden;
  letter-spacing: 0.02em;
  background-color: #00aeef;
}

.btn-style-one:hover {
  background-color: #0794c9;
  color: #ffffff;
}
.about-section {
  position: relative;
  padding: 120px 0 70px;
}

.about-section .sec-title {
  margin-bottom: 45px;
}

.about-section .content-column {
  position: relative;
  margin-bottom: 50px;
}

.about-section .content-column .inner-column {
  position: relative;
  padding-left: 30px;
}

.about-section .text {
  margin-bottom: 20px;
  font-size: 16px;
  line-height: 26px;
  color: #848484;
  font-weight: 400;
}

.about-section .list-style-one {
  margin-bottom: 45px;
}

.about-section .btn-box {
  position: relative;
}

.about-section .btn-box a {
  padding: 15px 50px;
}

.about-section .image-column {
  position: relative;
}

.about-section .image-column .text-layer {
  position: absolute;
  right: -110px;
  top: 50%;
  font-size: 325px;
  line-height: 1em;
  color: #ffffff;
  margin-top: -175px;
  font-weight: 500;
}

.about-section .image-column .inner-column {
  position: relative;
  padding-left: 80px;
  padding-bottom: 0px;
}
.about-section .image-column .inner-column .author-desc {
  position: absolute;
  bottom: 16px;
  z-index: 1;
  background: orange;
  padding: 10px 15px;
  left: 96px;
  width: calc(100% - 152px);
  border-radius: 50px;
}
.about-section .image-column .inner-column .author-desc h2 {
  font-size: 21px;
  letter-spacing: 1px;
  text-align: center;
  color: #fff;
  margin: 0;
}
.about-section .image-column .inner-column .author-desc span {
  font-size: 16px;
  letter-spacing: 6px;
  text-align: center;
  color: #fff;
  display: block;
  font-weight: 400;
}
.about-section .image-column .inner-column:before {
  content: "";
  position: absolute;
  width: calc(50% + 80px);
  height: calc(100% + 160px);
  top: -80px;
  left: -3px;
  background: transparent;
  z-index: 0;
  border: 44px solid #00aeef;
}

.about-section .image-column .image-1 {
  position: relative;
}
.about-section .image-column .image-2 {
  position: absolute;
  left: 0;
  bottom: 0;
}

.about-section .image-column .image-2 img,
.about-section .image-column .image-1 img {
  box-shadow: 0 30px 50px rgba(8, 13, 62, 0.15);
  border-radius: 46px;
}

.about-section .image-column .video-link {
  position: absolute;
  left: 70px;
  top: 170px;
}

.about-section .image-column .video-link .link {
  position: relative;
  display: block;
  font-size: 22px;
  color: #191e34;
  font-weight: 400;
  text-align: center;
  height: 100px;
  width: 100px;
  line-height: 100px;
  background-color: #ffffff;
  border-radius: 50%;
  box-shadow: 0 30px 50px rgba(8, 13, 62, 0.15);
  -webkit-transition: all 300ms ease;
  -moz-transition: all 300ms ease;
  -ms-transition: all 300ms ease;
  -o-transition: all 300ms ease;
  transition: all 300ms ease;
}
</style>
