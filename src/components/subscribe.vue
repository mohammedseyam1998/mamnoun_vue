<template>
    <div>
        <div class="subscribe">
        <div class="container">
            <div class="row">
                <div class="col-md-4 col12">
                    <div class="join">
                        <i class="far fa-envelope"></i>
                        <h3>اشترك بالقائمة البريدية</h3>
                    </div>
                </div>
                <div class="col-md-8 col-12">
                    <div class="input-group mb-3">

                        <input type="text" class="form-control" placeholder="بريدك الالكتروني ..."
                            aria-label="Example text with button addon" aria-describedby="button-addon1">
                        <div class="input-group-prepend">
                            <button class="btn btn-outline-secondary" type="button" id="button-addon1">اشتراك</button>
                        </div>
                    </div>
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
.subscribe {
  margin-bottom: 50px;
  .join {
    display: flex;
    align-items: center;
    svg {
      font-size: 35px;
      margin-left: 18px;
    }
    h3 {
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 0;
      text-align: right;
      white-space: nowrap;
    }
  }
  .input-group {
    justify-content: flex-end;
    input {
      max-width: 480px;
      height: 60px;
      border: solid 1px #000000;
      border-radius: 0;
    }
    button {
      width: 120px;
      height: 60px;
      background-color: #000000;
      color: #ffffff;
      font-size: 14px;
      font-weight: bold;
      &:hover {
        background-color: #ed0c6e;
        color: white;
      }
    }
  }
}
</style>