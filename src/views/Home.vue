<template>
  <div class="home">
    <header>
      <a href="/"><img src="../assets/logo.png"></a>
    </header>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <main>
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
  display flex
  flex-wrap wrap
.item
  width 49%
</style>
