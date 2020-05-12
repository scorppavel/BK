<template>
  <div class="bk-checkbox-card">
    <div class="img-checkbox">
      <img src="../assets/tomato.png">
    </div>
    <div class="text-checkbox">
      помидор
    </div>
    <div class="confirm-checkbox">
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.bk-checkbox-card {
  width: 232px;
  height: 304px;
  background-color: #fff;
  box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.05);
  border-radius: 10px;
}

.img-checkbox {
  display: flex;
}

.img-checkbox img {
  width: 150px;
  height: 150px;
  margin: auto;
}

.text-checkbox {
  color: #602F03;
  text-align: center;
  margin: 10px 0 32px 0;
}

.confirm-checkbox {
  display: flex;
}

.confirm-checkbox {
  width: 50px;
  height: 50px;
  margin: auto;
  box-shadow: 0px 5px 15px rgba(109, 171, 41, 0.25);
  background: #6DAB29;
  border-radius: 27.5px;
  background-image: url(../assets/confirm.svg) no-repeat center; 
}
</style>