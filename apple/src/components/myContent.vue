<template>
  <fieldset>
    <legend>
      <h2>这是内容组件</h2>
    </legend>
    <div class="div1"></div>
  </fieldset>
</template>

<script>
    export default {
        name: "myContent"
    }
</script>

<style scoped>
  .div1 {
    width: 500px;
    height: 500px;
    background-color: darkred;
    border-radius: 100%;
  }
</style>
