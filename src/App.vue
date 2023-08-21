<template>
  <div id="app">
    <router-view class="flex-right"/>
  </div>
</template>
<script>
export default{
  data(){
    return {
    }
  },
  methods:{
  
  }
}
</script>
<style lang="scss">
.box{
  width: 100%;
  height: 100%;
  margin: 0;
 padding: 0;
}
html,
body,
#app {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
  .flex-left{
    
  }
  .flex-right{
  }
}
.active{
  background-color: bisque;
}

</style>
