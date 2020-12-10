<template>
  <div id="app">
  <Header/>
    <!--    <img src="./assets/logo.png">-->
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/Header";
export default {
  name: 'App',
  components:{Header}
}
</script>

<style scoped lang="stylus" ref="stylesheet/stylus">
  .container
    font-size: 14px;
    color: #707070;

</style>
