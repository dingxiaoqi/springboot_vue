<template>
  <div id="app">
    <Header></Header>
    <el-button type="primary">按钮测试</el-button>
    <router-view/>
  </div>

</template>

<script>
  import Header from "@/components/Header";

  export default {
    name:"Layout",
    components:{
      Header
    }
  }
</script>

