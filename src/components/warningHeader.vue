<template>
  <div class="warning">
   <div class="warning-header">
        <p>{{msg}} - <a href="#">انقر هنا</a></p>

    </div>
  </div>
</template>

<script>
export default {
  name: 'warningHeader',
  props: {
    msg: String
  }
}
</script>

<style lang="scss" scoped>
.warning-header {
  background-color: rgba($color: #ed0c6e, $alpha: 0.07);
  width: 100%;
  height: 29px;
  display: flex;
  justify-content: center;
  align-items: center;
  p {
    font-size: 10px;
    text-align: center;
    color: #000000;
    margin: 0;
    a {
      font-weight: bold;
      color: #000000;
    }
  }
}
</style>
