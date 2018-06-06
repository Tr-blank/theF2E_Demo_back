<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <main>
      <div class="demoList">
        <div class="item">
          <p><a href>week 0</a></p>
        </div>
        <div class="item">
          <p><a href>week 1</a></p>
        </div>
        <div class="item">
          <p><a href>week 2</a></p>
        </div>
        <div class="item">
          <p><a href>week 3</a></p>
        </div>
      </div>
      <div class="messageNews">
       最新留言<router-link to="/about">前往留言區</router-link>
      </div>
    </main>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style scoped lang="stylus">
main
  max-width 1400px
  margin 0 auto
.demoList
  display flex
  flex-wrap wrap
  justify-content: space-between;
  padding 40px 10px
.item
  width 48%
  padding-top 100px
  margin 20px 0
  background-color #eee
  box-shadow: 1px 1px 3px 1px rgba(0,0,0,.2);
  border-radius: 3px;
  p
    background-color #fff
    margin 0
    padding 10px
</style>
