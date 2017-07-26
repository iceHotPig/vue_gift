<template>
  <div id="app">
    <iheader></iheader> 
    <div class="tab">
      <div class="tab_item">
        <router-link to="/goods">商品</router-link>
      </div>
      <div class="tab_item">
        <router-link to="/seller">商家</router-link>
      </div>
      <div class="tab_item">
        <router-link to="/ratings">评价</router-link>
      </div>
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
import iheader from './components/header/header.vue'
export default {
  name: 'app',
  components:{
    iheader:iheader
  }
}
</script>

<style>

</style>
