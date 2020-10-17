<template>
    <div>
        <div class="services">
        <div class="container">
            <div class="service-box">
                <div class="logo">
                    <i class="fas fa-shipping-fast"></i>
                </div>
                <div class="name">
                    شحن مجاني
                </div>
                <div class="description">
                    عند الشراء بأكثر من 499 ريال داخل المملكة
                </div>
            </div>
            <div class="service-box">
                <div class="logo">
                    <i class="fas fa-headphones-alt"></i>
                </div>
                <div class="name">
                    فريق خدمة العملاء
                </div>
                <div class="description">
                    يعمل لخدمتكم طوال أيام الأسبوع
                </div>
            </div>
            <div class="service-box">
                <div class="logo">
                    <div class="venus">
                        <i class="fas fa-venus"></i>
                    </div>
                    <div class="mars">
                        <i class="fas fa-mars"></i>
                    </div>
                </div>
                <div class="name">
                    الفئة
                </div>
                <div class="description">
                    منتجاتنا مناسبة للجنسين من 6 أشهر حتى 16 سنة
                </div>
            </div>
            <div class="service-box">
                <div class="logo">
                    <i class="fas fa-trademark"></i>
                </div>
                <div class="name">
                    العلامة التجارية
                </div>
                <div class="description">
                    علامة تجارية خاصة بنا، منتجات عالية الجودة وأصلية %100
                </div>
            </div>
        </div>
    </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
.services {
  padding: 93px 0 53px 0;
  .container {
    display: flex;
    justify-content: space-between;
    .service-box {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      position: relative;
      width: 100%;
      max-width: 290px;
      .logo {
        width: 51px;
        height: 51px;
        border: dashed 2px #000000;
        background-color: #ffffff;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        .venus {
          position: relative;
        }
        .mars {
          position: absolute;
          top: 0;
          transform: translate(2px, 16px);
        }
        svg {
          font-size: 23px;
          color: #000000;
        }
      }
      .name {
        font-size: 13px;
        font-weight: bold;
        color: #212121;
        margin: 6px 0 5px 0;
      }
      .description {
        font-size: 12px;
        color: #858189;
        text-align: center;
      }

      &:not(:last-child) {
        &::after {
          content: "";
          width: 1.1px;
          height: 56.1px;
          background-color: #e8e8e8;
          top: 50%;
          left: 2px;
          position: absolute;
        }
      }
    }
  }
}
</style>