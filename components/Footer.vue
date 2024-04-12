<template>
  <div class="footer">
    <div class="footer-content">
      <div class="footer-left">
        <div class="logo"></div>
        <div class="join"></div>
        <div class="downloadAPS"></div>
        <div class="downloadPS"></div>
      </div>
      <div class="footer-right"></div>
    </div>
    <div class="social-icons">
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
    </div>
  </div>
</template>
<style scoped>
.footer {
  position: relative;
  border: solid 1px black;
  padding: 130px 0 75px 0;
  height: 545px;
  background-color: rgb(123, 119, 119);
}
.footer-content {
  position: relative;
  border: solid 1px black;
  margin: 0 127px;
  padding: 0 35px;
  height: 403px;
  display: flex;
  flex-direction: row;
  /* align-items: space-between; */
}
.footer-left {
  position: relative;
  border: solid 1px black;
  display: flex;
  align-items: space-between;
  flex-direction: column;
  padding-left: 50px;
  width: 600px;
  height: 403px;
}
.logo {
  position: relative;
  border: solid 1px black;
  width: 134px;
  height: 18px;
}
.join {
  border: solid 1px black;
  width: 323px;
  height: 90px;
}
.downloadAPS {
  border: solid 1px black;
  width: 144px;
  height: 46px;
}
.downloadPS {
  border: solid 1px black;
  width: 144px;
  height: 46px;
}
.footer-right {
  border: solid 1px black;
  width: 650px;
  height: 403px;
  padding-left: 50px;
  margin-left: 50px;
}
/* .footer .social-icons {
  position: absolute;
  border: solid 1px black;
  width: 50px;
  height: 403px;
  display: flex;
  justify-content: space-around;
  list-style: none;
} */
</style>
