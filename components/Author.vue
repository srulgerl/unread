<template>
  <div class="author">
    <a href=""
      ><img
        class="author-img"
        src="https://unread.today/files/profile/00b063d23a6c69f2b1482fa084fddbf5.jpg"
        alt=""
    /></a>
    <div class="prof">
      <a href="">Unread Today</a>
      <p>4 сарын 13,2024 • 7 мин</p>
    </div>
  </div>
</template>
<style>
.author {
  position: relative;
  color: white;
  display: flex;
  flex-direction: row;
}
.author .author-img {
  height: 44px;
  width: 44px;
  border-radius: 50%;
}
.author .prof {
  display: flex;
  flex-direction: column;
  margin-right: 44px;
  font-size: 12.6px;
}
.author .prof a {
  font-weight: 700;
  text-decoration: none;
  color: white;
  border-radius: solid 1px white;
  opacity: 0.3;
}
.author .prof a:hover {
  color: #fff;
}
</style>
