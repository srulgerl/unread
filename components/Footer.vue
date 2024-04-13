<template>
  <div class="container">
    <div class="footer">
      <div class="footer-content">
        <div class="footer-left">
          <div class="logo">
            <a href="/">
              <img
                src="https://unread.today/files/site_meta/b809740220f5b5b4749e697e42df987b.png"
                alt="Logo"
            /></a>
          </div>
          <div class="contentniil">
            <div class="txt">
              <h6>Хамтран ажжиллах хүсэлт илгээх</h6>
              <p>Контент нийлүүлэх</p>
            </div>
            <div>
              <button></button>
            </div>
          </div>
          <div class="eventhamt"></div>
          <div class="download">
            <div class="downloadAPS"></div>
            <div class="downloadPS"></div>
          </div>
        </div>
        <div class="footer-right">
          <div class="right-nav">
            <a href="" class="a">Редакцын бодлого • </a>
            <a href="" class="b"> Блог • </a>
            <a href="" class="c"> Ажлын байр • </a>
            <a href="" class="d">Холбогдох</a>
          </div>
          <div class="copy-right">
            <p>
              © 2015-2024 Анрид Медиа ХХК. Бүх эрх хуулиар хамгаалагдсан.
              Контентуудыг зөвшөөрөлгүйгээр болон дурдалгүйгээр нийтлэх, хэвлэх,
              эш татахыг хориглоно.
            </p>
          </div>
          <div class="bulanguud">
            <div class="firstcol">
              <h5>Булангууд</h5>
              <a className="" href="/">Онцлох бизнес</a>
              <a href="/">Techworm</a>
              <a href="/">Би хэрхэн ажжилдаг вэ?</a>
              <a href="/">Мэдүүштэй</a>
              <a href="/">Чөлөөт</a>
              <a href="/">Номын тухай</a>
              <a href="/">7 хоногийн тойм</a>
            </div>
            <div class="seccol">
              <a href="/">Өртөөлэгчид</a>
              <a href="/">Тогтвортой хөгжил</a>
              <a href="/">Тайлбарлах нь</a>
              <a href="/">10 ертөнц, 10 өнцөг</a>
              <a href="/">Таатай оффис</a>
              <a href="/">Зочинтой булан</a>
              <a href="/">8 минутын улс төр</a>
            </div>
            <div class="thirdcol">
              <h5>Компани</h5>
              <p>
                Улаанбаатар 14240 <br />
                СБД, 8-р хороо, Амарын гудамж, <br />Тэнгэрлиг мидеа групп
              </p>
              <p>+976 9973 1632</p>
              <p>+976 8801 3893</p>
            </div>
          </div>
        </div>
        <div class="social-icons">
          <a href=""></a>
          <a href=""></a>
          <a href=""></a>
          <a href=""></a>
          <a href=""></a>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  position: relative;
  box-sizing: border-box;
  border: solid 1px black;
  padding: 130px 0 75px 0;
}
.footer {
  position: relative;
  border: solid 1px black;

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
  width: 600px;
  height: 403px;
}
.logo {
  position: relative;
  border: solid 1px black;
  margin: 0;
  width: 134px;
  height: 18px;
}

.contentniil {
  border: solid 1px black;
  width: 323px;
  height: 90px;
  margin-top: 49px;
}
.eventhamt {
  border: solid 1px black;
  width: 323px;
  height: 90px;
  margin-top: 22px;
}
.download {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  margin-top: 30px;
  width: 416px;
  height: 66px;
}
.downloadAPS {
  border: solid 1px black;
  width: 144px;
  height: 46px;
  margin-right: 10px;
}
.downloadPS {
  border: solid 1px black;
  width: 144px;
  height: 46px;
}
.footer-right {
  position: relative;
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
.right-nav {
  display: flex;
  margin: 0 0 46px 0;
  border: solid 1px black;
  width: 600px;
  height: 21px;
}
.righ-nav a {
  border: solid 1px black;
  display: flex;
  align-items: center;
  margin: 0 10px 0 10px;
}
/* .right-nav .b:before,
.right-nav .c:before,
.right-nav .d:before {
  content: ".";
  margin: 0 10px 0 8px;
  font-size: 40px;
} */
.footer-right > copy-right {
  margin: 15px 0;
  width: 500px;
  height: 26px;
  font-size: 1.8rem;
}
.bulanguud {
  border: solid 1px black;
  display: flex;
  justify-content: stretch;
  height: 264px;
  margin-top: 46px;
}
.firstcol,
.seccol,
.thirdcol {
  border: solid 1px black;
  width: 208px;
}
.firstcol h5 {
  margin-bottom: 15px;
}
.thirdcol h5 {
  margin-bottom: 15px;
  padding-bottom: 9px;
}
.firstcol,
.seccol {
  display: flex;
  flex-direction: column;
  padding-right: 28px;
}
.firstcol a,
.seccol a {
  margin-top: 9px;
}
.seccol {
  padding-top: 30px;
}
.footer-left p h6 {
  display: flex;
}
</style>
