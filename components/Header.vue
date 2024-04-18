<script>
export default {};
</script>
<template>
  <div class="header-container">
    <div class="header">
      <div class="menu">
        <span class="menu-line"></span>
        <span class="menu-line"></span>
        <span class="menu-line"></span>
      </div>
      <div class="nav">
        <div class="logosearch">
          <div class="logo">
            <a href="/">
              <img
                src="https://unread.today/files/site_meta/b809740220f5b5b4749e697e42df987b.png"
                alt="Logo"
            /></a>
          </div>
          <span class="divider"></span>
          <div class="search">
            <span
              ><i
                style="width: 30px; height: 30px"
                class="fa-solid fa-magnifying-glass"
              ></i
            ></span>
            <input type="text" placeholder="Хайлт хийх" />
          </div>
        </div>
        <div class="content">
          <span style="opacity: 0.5; color: #fff">Дараагийн нийтлэл:</span>
          <span style="margin-left: 5px; color: #fff; font-weight: 300"
            >Мэдүүштэй</span
          >
          <a class="chip">Маргааш орно</a>
        </div>
      </div>
      <div class="social-links">
        <a href="https://www.facebook.com/UnreadToday/">
          <i style="height: 100%" class="fa-brands fa-square-facebook"></i>
        </a>
        <a href="https://www.instagram.com/unreadtoday/">
          <i style="height: 100%" class="fa-brands fa-instagram"></i>
        </a>
        <a href="https://twitter.com/UnreadToday">
          <i style="height: 100%" class="fa-brands fa-twitter"></i>
        </a>
        <a href="https://www.linkedin.com/company/unreadmedia">
          <i style="height: 100%" class="fa-brands fa-linkedin-in"></i>
        </a>
      </div>
    </div>
  </div>
</template>
<style>
.header-container {
  position: absolute;
  width: 100%;
  display: flex;
  flex-direction: column;
  z-index: 1;
}
.header {
  position: absolute;
  display: flex;
  align-items: center;
  /* justify-content: space-around; */
  position: relative;
  margin: 0px 45px 0 45px;
  padding: 24px 0 19px 0;
  /* background-color: rgb(144, 144, 144); */
}
.menu {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 19px;
  height: 19px;
  left: 0;
  right: 0;
  position: absolute;
  cursor: pointer;
}
.menu-line {
  width: 19px;
  height: 3.5px;
  border-radius: 10px;
  background-color: white;
}
.menu-line:nth-child(1) {
  top: 0;
  width: 19px;
  height: 3px;
  font-weight: bold;
}
.menu-line:nth-child(2) {
  top: 7px;
  width: 11px;
  height: 3px;
}
.menu-line:nth-child(3) {
  top: 14px;
  width: 19px;
  height: 3px;
}
.nav {
  box-sizing: border-box;
  display: flex;
  justify-content: space-between;
  height: 41px;
  width: 100%;
  padding: 0 35px;
  left: 0;
  margin: 0 82px;
}

.logosearch {
  box-sizing: border-box;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
  padding: 0;
}

.logo img {
  width: 134px;
  height: 18px;
}

.divider {
  margin-left: 30px;
  margin-right: 17px;
  width: 1px;
  height: 18px;
  background-color: rgb(255, 255, 255);
}
.search span {
  color: #fff;
  opacity: 0.3;
}
.search > input {
  background: rgba(255, 255, 255, 0);
  padding: 10px;
}
.search > input:active {
  outline: none;
}
.search > input:focus {
  outline: none;
}
.search::placeholder {
  background-color: transparent;
  font-size: 20.16px;
  font-weight: 500;
  font: inherit;
  width: 120px;
  height: 30px;
  color: #fff;
}

.content {
  color: white;
  margin: 0 0 0 10px;
  font: normal 10px / 20px "SF Display", Helvetica, Arial, sans-serif;
}
.content span {
  font-size: 0.8rem;
}
.content span:nth-child(2) {
  text-transform: uppercase;
  font-weight: 600;
  margin-left: 5px;
}
.chip {
  display: inline-block;
  border-radius: 30px;
  margin: 0 0 0 10px;
  padding: 8px 18px;
  background-color: rgba(255, 255, 255, 0.5);
  font-size: 13px;
  cursor: pointer;
}
.social-links {
  color: #fff;
  position: absolute;
  right: 0;
  top: 34px;
  height: 20px;
  display: flex;
  align-items: center;
  list-style: none;
}

.social-links a {
  margin-left: 11px;
  display: flex;
  height: 15px;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  color: white;
  opacity: 0.3;
}
.social-links a:hover {
  cursor: pointer;
}

.social-links path {
  display: flex;
  align-items: center;
  justify-content: center;
  height: max-content;
  background-color: rgba(255, 255, 255, 0.5);
}
.social-icons a:nth-child(1):hover,
.fa-square-facebook:hover {
  opacity: 1;
  color: #475993 !important;
}
.social-icons a:nth-child(2):hover,
.fa-instagram:hover {
  opacity: 1;
  color: transparent !important;
  background: linear-gradient(45deg, #f9ce34, #ee2a7b, #6228d7);
  -webkit-background-clip: text;
  background-clip: text;
}
.social-icons a:nth-child(3):hover,
.fa-twitter:hover {
  opacity: 1;
  color: #1da1f2 !important;
}

.social-icons a:nth-child(4):hover,
.fa-linkedin-in:hover {
  opacity: 1;
  color: #0077b5 !important;
}
</style>
