<template>
  <div id="app">
    
    <router-view>    </router-view>

  </div>
</template>

<script>

  export default {
    name: 'el-view',
    methods: {
      clickBtn(){
        this.$router.push({path:'baidu'});
      }
    },
  }
</script>

<style>
  /* CSS */
</style>
