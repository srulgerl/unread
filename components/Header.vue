import type { setBlockTracking } from 'vue'; import type { setBlockTracking }
from 'vue'; import type { setBlockTracking } from 'vue'; import type {
setBlockTracking } from 'vue';
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
            <input type="text" placeholder="Хайлт хийх" />
          </div>
        </div>
        <div class="content">
          <span style="opacity: 0.5; color: rgb(255, 255, 255)"
            >Дараагийн нийтлэл:</span
          >
          <span style="margin-left: 5px; color: rgb(255, 255, 255)"
            >Мэдүүштэй</span
          >
          <a class="chip">Маргааш орно</a>
        </div>
      </div>
      <div class="social-links">
        <a href="https://www.facebook.com/UnreadToday/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="20px"
            height="20px"
            viewBox="0 0 50 50"
          >
            <path
              d="M41,4H9C6.24,4,4,6.24,4,9v32c0,2.76,2.24,5,5,5h32c2.76,0,5-2.24,5-5V9C46,6.24,43.76,4,41,4z M37,19h-2c-2.14,0-3,0.5-3,2 v3h5l-1,5h-4v15h-5V29h-4v-5h4v-3c0-4,2-7,6-7c2.9,0,4,1,4,1V19z"
            ></path>
          </svg>
        </a>
        <a href="https://www.instagram.com/unreadtoday/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="20px"
            height="20px"
            viewBox="0 0 50 50"
          >
            <path
              d="M 16 3 C 8.8324839 3 3 8.8324839 3 16 L 3 34 C 3 41.167516 8.8324839 47 16 47 L 34 47 C 41.167516 47 47 41.167516 47 34 L 47 16 C 47 8.8324839 41.167516 3 34 3 L 16 3 z M 16 5 L 34 5 C 40.086484 5 45 9.9135161 45 16 L 45 34 C 45 40.086484 40.086484 45 34 45 L 16 45 C 9.9135161 45 5 40.086484 5 34 L 5 16 C 5 9.9135161 9.9135161 5 16 5 z M 37 11 A 2 2 0 0 0 35 13 A 2 2 0 0 0 37 15 A 2 2 0 0 0 39 13 A 2 2 0 0 0 37 11 z M 25 14 C 18.936712 14 14 18.936712 14 25 C 14 31.063288 18.936712 36 25 36 C 31.063288 36 36 31.063288 36 25 C 36 18.936712 31.063288 14 25 14 z M 25 16 C 29.982407 16 34 20.017593 34 25 C 34 29.982407 29.982407 34 25 34 C 20.017593 34 16 29.982407 16 25 C 16 20.017593 20.017593 16 25 16 z"
            ></path>
          </svg>
        </a>
        <a href="https://twitter.com/UnreadToday">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="20px"
            height="20px"
            viewBox="0 0 50 50"
          >
            <path
              d="M 50.0625 10.4375 C 48.214844 11.257813 46.234375 11.808594 44.152344 12.058594 C 46.277344 10.785156 47.910156 8.769531 48.675781 6.371094 C 46.691406 7.546875 44.484375 8.402344 42.144531 8.863281 C 40.269531 6.863281 37.597656 5.617188 34.640625 5.617188 C 28.960938 5.617188 24.355469 10.21875 24.355469 15.898438 C 24.355469 16.703125 24.449219 17.488281 24.625 18.242188 C 16.078125 17.8125 8.503906 13.71875 3.429688 7.496094 C 2.542969 9.019531 2.039063 10.785156 2.039063 12.667969 C 2.039063 16.234375 3.851563 19.382813 6.613281 21.230469 C 4.925781 21.175781 3.339844 20.710938 1.953125 19.941406 C 1.953125 19.984375 1.953125 20.027344 1.953125 20.070313 C 1.953125 25.054688 5.5 29.207031 10.199219 30.15625 C 9.339844 30.390625 8.429688 30.515625 7.492188 30.515625 C 6.828125 30.515625 6.183594 30.453125 5.554688 30.328125 C 6.867188 34.410156 10.664063 37.390625 15.160156 37.472656 C 11.644531 40.230469 7.210938 41.871094 2.390625 41.871094 C 1.558594 41.871094 0.742188 41.824219 -0.0585938 41.726563 C 4.488281 44.648438 9.894531 46.347656 15.703125 46.347656 C 34.617188 46.347656 44.960938 30.679688 44.960938 17.09375 C 44.960938 16.648438 44.949219 16.199219 44.933594 15.761719 C 46.941406 14.3125 48.683594 12.5 50.0625 10.4375 Z"
            ></path>
          </svg>
        </a>
        <a href="https://www.linkedin.com/company/unreadmedia"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            x="0px"
            y="0px"
            width="20px"
            height="20px"
            viewBox="0 0 30 30"
          >
            <path
              d="M9,25H4V10h5V25z M6.501,8C5.118,8,4,6.879,4,5.499S5.12,3,6.501,3C7.879,3,9,4.121,9,5.499C9,6.879,7.879,8,6.501,8z M27,25h-4.807v-7.3c0-1.741-0.033-3.98-2.499-3.98c-2.503,0-2.888,1.896-2.888,3.854V25H12V9.989h4.614v2.051h0.065 c0.642-1.18,2.211-2.424,4.551-2.424c4.87,0,5.77,3.109,5.77,7.151C27,16.767,27,25,27,25z"
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>
<style>
.header-container {
  background-color: rgb(144, 144, 144);
}
.header {
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
  top: 36px;
  left: 0;
  right: 0;
  position: absolute;
  cursor: pointer;
}
.menu-line {
  width: 19px;
  height: 3.5px;
  border-radius: 10px;
  background-color: rgb(255, 255, 255);
}
.menu-line:nth-child(1) {
  top: 0;
  width: 19px;
  height: 3px;
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
}
.social-links {
  color: #fff;
  position: absolute;
  right: 0;
  top: 34px;
  height: 20px;
  display: flex;
  justify-content: space-around;
  list-style: none;
}

.social-links a {
  margin-left: 11px;
  display: flex;
  height: 19px;
  text-decoration: none;
  width: 15px;
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
</style>
