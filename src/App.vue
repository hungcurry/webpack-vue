<script>
import { reactive } from 'vue';
export default {
  setup () {
    const state = reactive({
      message: 'Vue3'
    })
    return {
      state,
    }
  }
}
</script>


<template>
  <div class="container">
    hello {{state.message}}
  </div>
  <div class="root"></div>
  <div class="food"></div>
  <div class="icon"></div>

  <div class="info">MyName</div>
  <div class="alert"></div>
  <div class="success"></div>

  <div class="box"></div>
  <a id="link" href="#">link</a>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;700&display=swap');
  body{
    font-family: 'Noto Sans TC', sans-serif;
  }
</style>
<style lang="scss" scoped>
body {
  .container {
    font-size:  100px;
    color: red;
  }
}
</style>
