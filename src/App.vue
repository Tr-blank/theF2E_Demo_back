<template>
  <body id="app">
    <header>
      <h1><router-link to="/">The F2E 前端修練精神時光屋<span>Tiya(提亞)作品展示</span></router-link></h1>
      <img src="./assets/logo.png">
    </header>
    <router-view/>
    <footer>Copyright © 2015 By <a href="/">Tiya(提亞)</a> All rights reserved</footer>
  </body>
</template>
 
<style lang="stylus">
body
  padding 0
  margin 0
h1
  font-size: 18px;
  font-weight: normal; 
#app
  font-family khula,Arial,Microsoft JhengHei ,sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50

#nav
  padding 30px
  a
    font-weight bold
    color #2c3e50
    &.router-link-exact-active
      color #42b983
footer
  background-color #eee
  color #a1a1a1
  font-size: 12px;
  padding 40px 10px
</style>
