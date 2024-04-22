<template>
  <nuxt-link to="/c/:name">
    <div class="content">
      <div class="title">
        <h6><a href="">Тогтвортой хөгжил</a></h6>
        <h3>
          <a href="">Coldplay хамтлагийн байгальд ээлтэй аялан тоглолт</a>
        </h3>
      </div>
      <div class="article-img">
        <a href=""
          ><img
            src="https://unread.today/files/2f1c26d7-6f24-46c8-9307-bbfecc8b41b1/a5d88da5e40fbd813500ce2b4f8cc986_square.png"
            alt=""
        /></a>
      </div>
    </div>
  </nuxt-link>
</template>
<style scoped>
.content {
  width: 623px;
  padding: 28px 65px 20px 51px;
  margin: 13px 0 0 0;
  background-color: #fff;
  color: black;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-start;
  border-radius: 0 27px 27px 27px;
  letter-spacing: 0.015rem;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 12px;
}
.content .title {
  text-decoration: none;
}
.content:hover {
  transform: translate(0, -5px);
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  transition: all 0.2s ease-in-out;
}
/* .author:hover {
  transform: translate(0, -5px);
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  transition: all 0.2s ease-in-out;
} */
.content h6 > a {
  color: #0078f6;
  font-size: 12.6px;
  text-decoration: none;
  letter-spacing: 0.03rem;
  font-weight: 550;
}
.content h6::before {
  content: "•";
  font-size: 1.8rem;
  position: absolute;
  display: flex;
  align-items: center;
  margin-left: -24px;
  color: #0078f6;
}
.content h3 {
  font-size: 21.6px;
  margin-bottom: 15px;
  font-weight: 600;
  line-height: 1.7rem;
}
.content h3 > a {
  padding-right: 180px;
  text-decoration: none;
  color: black;
}
.content .article-img img {
  width: 135px;
  height: 135px;
  border-radius: 50%;
  display: flex;
  justify-self: flex-end;
}
</style>
