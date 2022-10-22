<template>
    <div style="height: 50px;line-height: 50px;display: flex;border-bottom: 1px solid #cccccc" >
      <div style="width: 200px;">后台管理系统</div>
      <div style="flex:1"></div>
      <div style="width: 100px">
        <el-dropdown>
          <span class="el-dropdown-link">
            宇智波<i class="el-icon-arrow-down el-icon--right"></i>
          </span>
            <el-dropdown-menu slot="dropdown">
              <el-dropdown-item>个人中心</el-dropdown-item>
              <el-dropdown-item>退出</el-dropdown-item>
            </el-dropdown-menu>
          </el-dropdown>
      </div>
    </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>