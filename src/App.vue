<template>
<body>
  <div class="box">
  <div class="headportrait">
    <img class="head" src="./assets/head.png" alt=" Vue logo">
  </div>
  <div class="written">
    <span>305打印室</span> 
  </div>
  <span class="notes">用微信或企业微信扫码加入</span>
  <div class="img">
    <img class="QR" src="./assets/QR.png" alt=" Vue logo">
  </div>
  <div class="tipsbox">
    <span class="tips">该二维码7天内有效，重新进入将更新</span>
  </div>
</div>
</body>
</template>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  padding: 0;
  margin: 0;
  text-decoration: none;
  box-sizing: border-box;

}
body {
  background-color: rgb(240, 240, 240);
}
.box {
  width: 350px;
  height: 450px;
  border: 1px solid #ccc;
  border-radius: 10px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  background-color: rgb(255, 254, 254);
}
.headportrait {
  float: left;
  margin-top: 30px;
  margin-left: 30px;
}
.head {
  width: 75px;
  border-radius: 10px;
}
span {
  font-size: 30px;
}
.notes {
  color: rgb(172, 168, 168);
  font-size: 14px;
}
.written {
  margin-top: 45px;
}
.QR {
  width: 60%;
   border-radius: 20px;
}
.img {
  margin-top: 50px;
 
}
.tips {
  color: rgb(110, 109, 109);
  font-size: 14px;
}
.tipsbox {
  margin-top: 30px;
}
</style>