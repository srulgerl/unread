<template>
  <div class="menu">
    <span class="menu-line"></span>
    <span class="menu-line"></span>
    <span class="menu-line"></span>
  </div>
</template>
<style>
.menu {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 19px;
  height: 19px;
  cursor: pointer;
}
.menu-line {
  width: 19px;
  height: 3.5px;
  padding: 1;
  border-radius: 10px;
  background-color: white;
}
.menu-line:nth-child(2) {
  width: 11px;
  height: 3px;
}
</style>
