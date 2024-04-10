import type { setBlockTracking } from 'vue'; import type { setBlockTracking }
from 'vue'; import type { setBlockTracking } from 'vue'; import type {
setBlockTracking } from 'vue';
<script>
export default {};
</script>
<template>
  <div class="header">
    <div class="nav">
      <Menu></Menu>
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
      <div class="navbar-content">
        <span style="opacity: 0.5">Дараагийн нийтлэл:</span>
        <span style="margin-left: 5px">Мэдүүштэй</span>
        <a class="chip">Маргааш орно</a>
      </div>
      <div class="contacts">
        <ul>
          <li>
            <a href="https://www.facebook.com/UnreadToday/"
              ><img
                src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.vecteezy.com%2Fpng%2F18930698-facebook-logo-png-facebook-icon-transparent-png&psig=AOvVaw0KY8WsJBGkHSMqhrmwyjhg&ust=1712829809650000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMD42bSyt4UDFQAAAAAdAAAAABAE"
            /></a>
          </li>
          <li>
            <a href="https://www.instagram.com/unreadtoday/"><img src="" /></a>
          </li>
          <li>
            <a href="https://twitter.com/UnreadToday"><img src="" /></a>
          </li>
          <li>
            <a href="https://www.linkedin.com/company/unreadmedia"
              ><img src=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
    <span class="material-icons">mdi-close</span>
    <span class="material-icons">face</span>
  </div>
</template>
<style>
* {
  margin: 0;
  padding: 0;
}
.header {
  margin: 0px 45px 0 45px;
  padding: 24px 0 19px 0;
}
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 8px 0;
}
.logo img {
  width: 134px;
  height: 18px;
}
.divider {
  width: 1px;
  height: 18px;
  background-color: white;
}
.contacts ul {
  display: flex;
  justify-content: flex-end;
  list-style: none;
}
.contacts ul a {
  padding: 10px;
  text-decoration: none;
}
.navbar-content {
  margin-top: 1;
  color: white;
  display: flex;
  align-items: center;
  position: relative;
}
.chip {
  margin: 0 0 0 10px;
  padding: 8px 18px;
  color: #fff;
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 30px;
  /* border: 3.5px rgba(255, 255, 255, 0.5); */
  font-size: 0.92rem;
  display: flex;
}
.search > input {
  background: rgba(255, 255, 255, 0);
  padding: 10px;
  border: solid 0 rgba(0, 0, 0, 0);
}
</style>
