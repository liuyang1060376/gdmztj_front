<template>
  <div id="app">
  <Header/>
    <Nav />
    <!--    <img src="./assets/logo.png">-->
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/Header";
import Nav from "./components/Nav";
export default {
  name: 'App',
  components:{Header,Nav}
}
</script>

<style scoped lang="stylus" ref="stylesheet/stylus">
  .container
    font-size: 14px;
    color: #707070;

</style>
