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
              <h5>Хамтран ажжиллах хүсэлт илгээх</h5>
              <p>Контент нийлүүлэх</p>
            </div>
            <div>
              <button></button>
            </div>
          </div>
          <div class="eventhamt">
            <div class="txt">
              <h5>Хамтран ажиллах хүсэлт илгээх</h5>
              <p>Эвент хамтрах</p>
            </div>
            <div>
              <button></button>
            </div>
          </div>
          <div class="download">
            <div class="downloadAPS">
              <img
                style="width: 100%; height: 100%"
                src="https://unread.today/img/app_android.png"
                alt=""
              />
            </div>
            <div class="downloadPS">
              <img
                style="width: 100%; height: 100%"
                src="https://unread.today/img/app_ios.png"
                alt=""
              />
            </div>
          </div>
        </div>
        <div class="footer-right">
          <div class="right-nav">
            <a href="" class="a">Редакцын бодлого </a>
            <a href="" class="b"> Блог </a>
            <a href="" class="c"> Ажлын байр </a>
            <a href="" class="d">Холбогдох</a>
          </div>
          <div class="copy-right">
            <p>
              © 2015-2024 Анрид Медиа ХХК. Бүх эрх хуулиар хамгаалагдсан.
              Контентуудыг <br />зөвшөөрөлгүйгээр болон дурдалгүйгээр нийтлэх,
              хэвлэх, эш татахыг хориглоно.
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
      </div>
      <div class="social-icons">
        <a style="color: white" href="https://www.facebook.com/UnreadToday/"
          ><i style="font-size: 34px" class="fa-brands fa-square-facebook"></i>
        </a>
        <a style="color: white" href="https://twitter.com/UnreadToday"
          ><i style="font-size: 34px" class="fa-brands fa-twitter"></i
        ></a>
        <a style="color: white" href="https://www.instagram.com/unreadtoday/"
          ><i style="font-size: 34px" class="fa-brands fa-instagram"></i
        ></a>
        <a
          style="color: white"
          href="https://www.linkedin.com/company/unreadmedia"
          ><i style="font-size: 34px" class="fa-brands fa-linkedin-in"></i
        ></a>
        <a
          style="color: white"
          href="https://www.youtube.com/channel/UCfJkXzS4l7Rbq5rRgvHdsKw"
          ><i style="font-size: 34px" class="fa-brands fa-youtube"></i>
        </a>
        <a style="color: white" href="https://soundcloud.com/unreadtoday"
          ><i style="font-size: 34px" class="fa-brands fa-soundcloud"></i>
        </a>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  position: relative;
  background-color: black;
  padding: 130px 0 75px 0;
  font-family: "SF Display", Helvetica, Arial, sans-serif;
  font-size: 12.6px;
  font-stretch: 100%;
}
.footer {
  position: relative;
  background-color: rgb(0, 0, 0);
  display: flex;
  flex-direction: column;
}
.footer-content {
  position: relative;
  margin: 0 127px;
  padding: 0 35px;
  height: fit-content;
  display: flex;
  flex-direction: row;
  /* align-items: space-between; */
}
.footer-left {
  position: relative;
  display: flex;
  align-items: space-between;
  flex-direction: column;
  width: 600px;
}
.logo {
  position: relative;

  margin: 0;
  width: 134px;
  height: 18px;
}

.contentniil {
  width: 323px;
  margin-top: 49px;
  border: solid 1px rgb(217, 214, 214);
  border-radius: 18px;
  cursor: pointer;
}
.eventhamt {
  width: 323px;
  margin-top: 22px;
  border: solid 1px rgb(195, 192, 192);
  border-radius: 18px;
  cursor: pointer;
}
.footer-left .contentniil,
.eventhamt {
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
  flex-direction: row;
  padding: 21px 80px 27px 28px;
  width: 215px;
  height: 42px;
  color: white;
}
.footer-left button {
  position: absolute;
  width: 36px;
  height: 36px;
  top: 50%;
  transform: translate(0, -50%);
  border: solid 9px;
  border-radius: 50%;
}
.footer-left .txt {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.txt p {
  font-size: 1.1em;
}
.footer-left h5 {
  font-weight: 400;
  opacity: 0.3;
  letter-spacing: 0.03rem;
  line-height: 20px;
}
.download {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  margin-top: 30px;
  width: 416px;
  height: 66px;
  cursor: pointer;
}
.downloadAPS {
  width: 144px;
  height: 46px;
  margin-right: 10px;
}
.downloadPS {
  width: 144px;
  height: 46px;
}
.footer-right {
  position: relative;

  width: 600px;
  height: 370px;
  padding-left: 50px;
  margin-left: 50px;
}
/* .footer .social-icons {
  position: absolute;

  width: 50px;
  height: 403px;
  display: flex;
  justify-content: space-around;
  list-style: none;
} */
.right-nav {
  display: flex;
  margin: 0 0 46px 0;
  width: 600px;
  height: 21px;
}
.right-nav a {
  display: flex;
  align-items: center;
  color: white;
  text-decoration: none;
  font-size: 1.14em;
}
.right-nav .b:before,
.right-nav .c:before,
.right-nav .d:before {
  content: "•";
  margin: 0 10px 0 8px;
  color: white;
  text-decoration: none;
}
.right-nav a:hover {
  opacity: 0.8;
}
.b:before:hover,
.c:before:hover,
.d:before:hover {
  opacity: 0.8;
}
.footer-right .copy-right {
  margin: 15px 0;
  width: 500px;
  height: 26px;
  color: #878787;
}
.copy-right p {
  font-size: 0.9em !important;
}
.footer-right p {
  color: #878787;
}
.bulanguud {
  display: flex;
  justify-content: stretch;
  height: 264px;
  margin-top: 46px;
}
.bulanguud a:hover {
  transform: translate(3px, -2px);
  transition: all 0.2s ease-in-out;
  color: #fff;
}
.firstcol,
.seccol,
.thirdcol {
  width: 208px;
}
.firstcol h5 {
  margin-bottom: 15px;
  font-size: 15px;
  font-weight: 700;
  color: #0078f6;
  transition: all 0.2s ease-in-out;
}
.thirdcol h5 {
  margin-bottom: 15px;
  padding-bottom: 9px;
  font-size: 15px;
  color: #0078f6;
}
.thirdcol p {
  color: #878787;
  margin-top: 5px;
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
  color: #878787;
  text-decoration: none;
  line-height: 1.2em;
}
.seccol {
  padding-top: 30px;
}

.footer .social-icons {
  display: flex;
  justify-content: start;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 70px;
  margin: 70px 127px 0 127px;
}
.social-icons a {
  width: 157px;
  padding: 20px 0 20px 0;
  margin-left: 33px;
  display: flex;
  justify-content: center;
  text-decoration: none;
  opacity: 0.3;
}
.social-icons a:nth-child(1) {
  display: flex;
  justify-content: flex-start !important;
}
.social-icons a:nth-child(6) {
  display: flex;
  justify-content: flex-end !important;
}
.social-icons a:nth-child(1):hover,
.fa-square-facebook:hover {
  opacity: 1;
  color: #475993 !important;
}
.social-icons a:nth-child(2):hover,
.fa-twitter:hover {
  opacity: 1;
  color: #1da1f2 !important;
}
.social-icons a:nth-child(3):hover,
.fa-instagram:hover {
  opacity: 1;
  color: transparent !important;
  background: linear-gradient(45deg, #f9ce34, #ee2a7b, #6228d7);
  -webkit-background-clip: text;
  background-clip: text;
}
.social-icons a:nth-child(4):hover,
.fa-linkedin-in:hover {
  opacity: 1;
  color: #0077b5 !important;
}
.social-icons a:nth-child(5):hover,
.fa-youtube:hover {
  opacity: 1;
  color: #ff0000 !important;
}
.social-icons a:nth-child(6):hover,
.fa-soundcloud:hover {
  opacity: 1;
  color: #ff5500 !important;
}
</style>
