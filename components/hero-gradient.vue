import type { Header } from '#build/components';
<template>
  <div class="bg">
    <Header></Header>
  </div>
</template>
<style>
.bg {
  background-image: linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0) 40%,
      rgba(0, 0, 0, 1) 100%
    ),
    url("/Users/saruulgerelotgonbaatar/Documents/intern/unread/unread/public/assests/hero-grad_bg.jpg");
  background-size: cover;
  height: 80vh;
}
</style>
