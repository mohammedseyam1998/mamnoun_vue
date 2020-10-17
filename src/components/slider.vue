<template>
  <div>
      <div class="slider">
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="lazyload d-block w-100" src="../assets/collection.png"
                        alt="collection">
                </div>
                <div class="carousel-item">
                    <img class="lazyload d-block w-100"  src="../assets/collection.png"
                        alt="collection">
                </div>
                <div class="carousel-item">
                    <img class="lazyload d-block w-100"  src="../assets/collection.png"
                        alt="collection">
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </div>
  </div>  
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.slider {
  .carousel-indicators {
    li {
      width: 15px;
      height: 15px;
      border-radius: 50%;
      border-bottom: none !important;
      border-top: none !important;
    }
    .active {
      box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.16);
      background-color: #000000;
    }
  }
}
</style>