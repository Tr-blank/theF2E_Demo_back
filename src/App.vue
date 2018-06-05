<template>
  <body id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
    <footer>Copyright © 2015 By <a href="/">Tiya(提亞)</a> All rights reserved</footer>
  </body>
</template>

<style lang="stylus">
body
  padding 0
  margin 0
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
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
