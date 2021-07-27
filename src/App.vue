<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view name="header"/>
    <router-view name="main" class="site-content" />
    <router-view name="Nav" />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
.site-content{
  padding-right: 30vw;
  padding-left: 30vw;
  max-width: 1080px;
}
@media only screen and(min-width:1001px){
  .site-content{
    margin-left: 30vw;
    padding-bottom: 3.33333em;
    padding-top: 3.33333em;
  }
}
@media only screen and(min-width:801px)and(max-width:1001px){
  .site-content{
    margin-left: 30vw;
    padding-left: 3.33333em;
    padding-top: 3.33333em;
  }}
  @media only screen and(max-width:800px){

  }

</style>
