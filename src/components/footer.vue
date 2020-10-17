<template>
    <div>
        <footer>
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-3">
                    <div class="about-us">
                        <div class="title">
                            عن ممنون
                        </div>
                        <p>هذا النص هو مثال لنص يمكن أن يستبدل في نفس المساحة، لقد تم توليد هذا النص من مولد النص
                            العربى،
                            حيث يمكنك أن تولد مثل هذا النص أو العديد من النصوص الأخرى إضافة إلى زيادة عدد الحروف التى
                            يولدها
                            التطبيق.
                        </p>
                        <div class="social-links">
                            <a href="#">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#"><i class="fab fa-twitter"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-2 col-6">
                    <div class="about-us">
                        <div class="title">
                            معلومات
                        </div>
                        <ul>
                            <a href="#">
                                <li>الرابط هنا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هناااا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هنااااااا
                                </li>
                            </a>
                            <a href="#">
                                <li>الرابط هنا بالكامل</li>
                            </a>
                        </ul>
                    </div>
                </div>
                <div class="col-6 col-md-2">
                    <div class="about-us">
                        <div class="title">
                            خدمة العملاء
                        </div>
                        <ul>
                            <a href="#">
                                <li>الرابط هنا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هناااا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هنااااااا
                                </li>
                            </a>
                            <a href="#">
                                <li>الرابط هنا بالكامل</li>
                            </a>
                        </ul>
                    </div>
                </div>
                <div class="col-6 col-md-2">
                    <div class="about-us">
                        <div class="title">
                            روابط مساعدة
                        </div>
                        <ul>
                            <a href="#">
                                <li>الرابط هنا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هناااا</li>
                            </a>
                            <a href="#">
                                <li>الرابط هنااااااا
                                </li>
                            </a>
                            <a href="#">
                                <li>الرابط هنا بالكامل</li>
                            </a>
                        </ul>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="about-us">
                        <div class="title">
                            حمل التطبيق الآن
                        </div>
                        <div class="app-btn">
                            <button class="btn">
                                <div class="text">
                                    <span>Download on the</span>
                                    <h6>App Store</h6>
                                </div>
                                <div class="icon">
                                    <i class="fab fa-apple"></i>
                                </div>
                            </button>
                        </div>
                        <div class="google-btn">
                            <button class="btn">
                                <div class="text">
                                    <span>Get it on</span>
                                    <h6>Google Play</h6>
                                </div>
                                <div class="icon">
                                    <i class="fab fa-google-play"></i>
                                </div>
                            </button>
                        </div>
                        <div class="cards">
                            <img src="img/Group 9948.png" alt="card">
                            <img src="img/Paypal.png" alt="card">
                            <img src="img/Group 19.png" alt="card">
                            <img src="img/Western-union.png" alt="card">

                        </div>
                    </div>
                </div>

            </div>
            <hr>
            <div class="rights">
                جميع الحقوق محفوظة © 2020
            </div>
        </div>
    </footer>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
footer {
  background-color: #000000;
  padding: 48px 0 36px 0;
  text-align: right;
  .container {
    .about-us {
      margin-left: 9px;
      .title {
        font-size: 18px;
        color: #c1c8ce;
        margin-bottom: 25px;
      }
      p {
        font-size: 12px;
        color: #ffffff;
      }
      .social-links {
        svg {
          font-size: 13px;
        }
        .fa-facebook-f {
          color: #385c8e;
          margin-left: 29px;
        }
        .fa-twitter {
          color: #03a9f4;
        }
      }
      ul {
        list-style: none;
        a {
          li {
            font-size: 14px;
            color: #ffffff;
            line-height: 2.29;
          }
        }
      }
      .app-btn,
      .google-btn {
        width: 146px;
        height: 40px;
        border: solid 1px #000000;
        background-color: #ffffff;
        button {
          display: flex;
          width: 100%;
          justify-content: space-evenly;
          padding-top: 2px;
          align-items: center;
          padding-bottom: 0;
          .text {
            color: #000000;
            text-align: left;
            display: flex;
            flex-direction: column;
            span {
              font-size: 8px;
            }
            h6 {
              font-size: 14px;
              font-weight: bold;
            }
          }
          .icon {
            svg {
              font-size: 24px;
              color: #000000;
            }
            .fa-google-play {
              font-size: 18px;
            }
          }
        }
      }
      .app-btn {
        margin-bottom: 6px;
      }
      .cards {
        display: flex;
        justify-content: space-between;
        width: 146px;
        margin-top: 16px;
      }
    }
    hr {
      width: 100%;
      height: 2px;
      background-color: #f6f7f8;
      margin-bottom: 32px;
    }
    .rights {
      text-align: center;
      color: #c1c8ce;
      font-size: 14px;
    }
  }
}

</style>