<template>
  <!-- logo.pngを自分で入れた画像の名前に変更 -->
  <img alt="Vue logo" src="./assets/penguin.jpg" />
  <!-- msg内に好きな言葉を入力 -->
  <HelloWorld msg="I Love Coke" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
