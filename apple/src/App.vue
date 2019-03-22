<template>
  <div id="app">
    <MyHeader></MyHeader>
    <my-content></my-content>
    <footer></footer>
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader";
import MyContent from "./components/myContent";
import Footer from "./components/footer";
export default {
  name: 'App',
  components: {Footer, MyContent, MyHeader}
}
</script>

<style>

</style>
