<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">首页 </router-link>|
      <router-link to="/about">关于</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #2d8cf0;
    }
  }
}
.ivu-modal-header {
  border-bottom: none !important;
  padding: 0 !important;
  line-height: 1;
}
</style>
