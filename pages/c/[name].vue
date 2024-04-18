<template>
  <div class="container">
    <div class="article">
      <div class="main-container">
        <a class="back_button" href="">&lt<span></span></a>
        <div class="text">
          <a href="">7 Хоногийн Тойм</a>
          <span>4 САРЫН 14, 2024</span>
          <span class="dot">6 МИН</span>
        </div>
        <h1>Samsung-ийн сэргэлт + Монгол хэлтэй AI + Erxes-ийн амжилт</h1>
        <a href=""
          ><img
            class="main-img"
            src="https://unread.today/files/44/e4207680c14a2d169599922ca8e1948e.png"
            alt=""
        /></a>
        <div class="content">
          <div class="left">
            <div class="author">
              <a href=""
                ><img
                  src="https://unread.today/files/profile/00b063d23a6c69f2b1482fa084fddbf5.jpg"
                  alt=""
              /></a>
              <div class="prof">
                <a href="">Unread Today</a>
                <p>4 сарын 13,2024 • 7 мин</p>
              </div>
            </div>
          </div>
          <div class="middle">
            <div class="handalt">
              <span>Хандалт/Сэтгэгдэл:</span>
              <i class="fa-solid fa-eye"></i>
            </div>
          </div>
          <div class="right"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.container {
  background-color: #fafafa;
  margin: 0;
  padding: 0;
  font-family: "SF Display", sans-serif;
}
.container .article {
  margin: 0 45px;
  padding: 109px 0 0 0;
}
.container .article .main-container {
  position: relative;
  margin: 0 82px;
  padding: 0 35px;
}
.main-container .text {
  margin-bottom: 15px;
  font-size: 12.6px;
  text-transform: uppercase;
  font-weight: 500;
  height: 22px;
}

.main-container .text a {
  text-decoration: none;
  margin-right: 10px;
  color: #0078f6;
}
.main-container .text a:hover {
  color: #005cc3;
}
.main-container .text span {
  color: #6d7378;
}
.main-container .text .dot:before {
  content: "•";
  margin: 0 9px 0 7px;
  font-size: 17px;
}
.main-container h1 {
  margin-bottom: 66px;
  font-size: 32px;
}
.container .article .back_button {
  position: absolute;
}
.container .article .main-img {
  width: 100%;
}
.container .main-container .content {
  display: flex;
  flex-direction: row;
  margin: 40px 0 0 -35px;
}
.main-container .content .left .author {
  position: relative;
  color: black;
  display: flex;
  flex-direction: row;
  align-items: space-between;
}
.main-container .content .left .author img {
  height: 36px;
  width: 36px;
  margin-right: 15px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.main-container .content .left .author .prof {
  display: flex;
  flex-direction: column;
  margin-right: 44px;
}
.main-container .content .left .author .prof a {
  text-decoration: none;
  color: black;
  font-size: 0.8rem;
}
.main-container .content .left .author .prof p {
  color: #888888;
  font-size: 0.8rem;
}
</style>
