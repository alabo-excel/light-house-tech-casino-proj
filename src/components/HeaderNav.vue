script
<template>
  <div class="">
    <div class="flex lg:hidden justify-between">
      <img src="../assets/icons/bell.png" alt="" />
      <img src="../assets/icons/bar.png" alt="" />
    </div>
    <div class="flex lg:mx-32 py-2 justify-between sm:hidden">
      <div class="flex">
        <img src="../assets/yt.png" alt="" />
        <img src="../assets/ig.png" alt="" />
        <img src="../assets/fb.png" alt="" />
        <img src="../assets/tg.png" alt="" />
      </div>
      <div class="my-1">
        <button class="btn mx-2 btn-login p-2">Login</button>
        <button class="btn mx-2 btn-signup p-2">Signup</button>
      </div>
    </div>
    <div class="btn-signup w-full h-1"></div>
    <div class="flex lg:mx-32 text-white uppercase sm:hidden">
      <div class="p-4 bg-gray-600">app download</div>
      <div class="p-4 btn-signup">Home</div>
      <div class="p-4 hover:bg-gray-600">live casino</div>
      <div class="p-4 hover:bg-gray-600">sports</div>
      <div class="p-4 hover:bg-gray-600">lotery</div>
      <div class="p-4 hover:bg-gray-600">teen patti</div>
      <div class="p-4 hover:bg-gray-600">card game</div>
      <div class="p-4 hover:bg-gray-600">slot</div>
      <div class="p-4 hover:bg-gray-600">promotion</div>
      <div class="p-4 hover:bg-gray-600">customer</div>
    </div>
  </div>
</template>

<style scoped>
img {
  width: 30px;
  margin: 10px;
  height: 30px;
}
.btn {
  color: white;
  border-radius: 5px;
  width: 100px;
}
.btn-login {
  background-color: rgb(158, 12, 12);
}
.btn-signup {
  background-image: url("../assets/bg-gold.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>