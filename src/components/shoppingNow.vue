<template>
    <div>
          <div class="shopping-now">
        <div class="container">
            <div class="title">
                تسوق حسب التصنيف
            </div>
            <div class="categories">
                <div class="category-box">
                    <img class="lazyload"  src="../assets/boy.png" alt="boys">
                    <h3 class="box-title">أزياء الأولاد</h3>
                    <div class="layer"></div>
                </div>

                <div class="category-box">
                    <img class="lazyload" src="../assets/girl.png" alt="boys">
                    <h3 class="box-title">أزياء الشتاء</h3>
                    <div class="layer"></div>
                </div>
                <div class="category-box">
                    <img class="lazyload"  src="../assets/girl2.png" alt="boys">
                    <h3 class="box-title">أزياء البنات</h3>
                    <div class="layer"></div>
                </div>
                <div class="category-box">
                    <img class="lazyload"  src="../assets/shose.png" alt="boys">
                    <h3 class="box-title">أحذية الأولاد</h3>
                    <div class="layer"></div>
                </div>
                <div class="category-box">
                    <img class="lazyload"  src="../assets/girl3.png" alt="boys">
                    <h3 class="box-title">اكسسوارات</h3>
                    <div class="layer"></div>
                </div>
                <div class="category-box">
                    <img class="lazyload"  src="../assets/shose2.png" alt="boys">
                    <h3 class="box-title">أحذية البنات</h3>
                    <div class="layer"></div>

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
.shopping-now {
  padding: 57px 0 71px 0;
  .title {
    position: relative;
    font-size: 23px;
    font-weight: bold;
    text-align: center;
    margin-bottom: 34px;
    &:after {
      content: "";
      height: 1px;
      position: absolute;
      background-color: rgba($color: #000000, $alpha: 0.29);
      top: 65%;
      left: 0;
      width: 100%;
      max-width: 418px;
      transform: translate(0, -65%);
    }
    &:before {
      content: "";
      height: 1px;
      position: absolute;
      background-color: rgba($color: #000000, $alpha: 0.29);
      top: 65%;
      right: 0;
      width: 100%;
      max-width: 418px;
      transform: translate(0, -65%);
    }
  }
  .categories {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    .category-box {
      position: relative;
      width: 356px;
      height: 434px;
      overflow: hidden;
      margin-bottom: 67px;
      border: solid 3px white;
      transition: all ease 0.5s;

      img {
        width: 100%;
        object-fit: contain;
        transition: all ease 0.8s;
      }
      .box-title {
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translate(-50%, -50%);
        color: #212121;
        font-size: 36px;
        font-weight: bold;
        z-index: 1;
        white-space: nowrap;
      }
      .layer {
        opacity: 0.87;
        background-image: linear-gradient(
          to bottom,
          rgba(255, 255, 255, 0),
          #ffffff
        );
        position: absolute;
        top: 0;
        left: 0;
        width: 357px;
        height: 434px;
      }
      &:hover {
        border: solid 3px #000000;
        img {
          transform: scale(0.9);
        }
      }
    }
  }
}
</style>