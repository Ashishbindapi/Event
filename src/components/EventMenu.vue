<template>
  <div class="container">
    <div class="row">
      <div class="col-4 mt-3">
        <img class="img-fluid img1" src="../assets/Asset 72png.png" alt="">
      </div>
      <div class="col-4 mt-2">
        <div class="col-12 mt-3">
          <img class="img-fluid img2 mt-5 ml-3" src="../assets/Asset 59png.png" alt="">
        </div>
        <div class="col-12 mt-2">
          <h5 class="text-danger ml-5">WHICH IS THE</h5>
        </div>
        <div class="col-12">
          <p class="text-warning text">UPCOMING EVENT</p>
        </div>
        <div class="col-12">
          <img class="img-fluid img2 ml-3" src="../assets/Asset 59png.png" alt="">
        </div>
      </div>
      <div class="col-4"></div>
    </div>
    <div class="row">
      <div class="col-2 mt-3">
        <div class="row mt-5 position-relative">
          <img class="img-fluid imgf" src="../assets/Asset 64png.png" alt="">
          <p class="position-absolute text-dark">शुभविवाह</p>
        </div>
        <div class="row mt-5 position-relative">
          <img class="img-fluid imgf" src="../assets/Asset 64png.png" alt="">
          <p class="position-absolute text-dark">जन्मदिन</p>
        </div>
      </div>
      <div class="col-4 mt-5">
        <img class="img-fluid mt-2 imgl" src="../assets/Asset 71png.png" alt="">
      </div>
      <div class="col-2 mt-3">
        <div class="row mt-5 position-relative2">
          <img class="img-fluid imgf2" src="../assets/Asset 64png.png" alt="">
          <p class="position-absolute2 text-dark">थीमपार्टी</p>
        </div>
        <div class="row mt-5 position-relative2">
          <img class="img-fluid imgf2" src="../assets/Asset 64png.png" alt="">
          <p class="position-absolute2 text-dark">सालगिरह</p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12 mt-2">
        <img class="img-fluid imgs" src="../assets/Asset 65png.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'EventMenu',
};
</script>

<style scoped>
.img1 {
  margin-top: 8px;
  width: 200px;
}

.img2 {
  width: 200px;
}

.imgf {
  width: 150px;
  margin-left: 350px;
}

.imgf2 {
  width: 150px;
}

.imgs {
  margin-top: 5px;
  max-width: 300px;
  margin-left: 365px;
}

.ml-5 {
  margin-left: 75px;
}

.ml-3 {
  margin-left: 40px;
}

.imgl {
  width: 0.3%;
  height: 150px;
  margin: 0%;
  padding: 0%;
  margin-left: 330px;
}

.text {
  font-size: 33px;
  color: rgb(11, 1, 1);
}

.position-relative {
  position: relative;
}

.position-absolute {
  position: absolute;
  top: 50%;
  margin-left: 470px;
  transform: translate(-50%, -50%);
  font-size: 20px;
  color: rgb(11, 1, 1);
}
.position-relative2 {
  position: relative;
}

.position-absolute2 {
  position: absolute;
  top: 50%;
  left: 65%;
  transform: translate(-50%, -50%);
  font-size: 20px;
  color: rgb(11, 1, 1);
}
</style>
