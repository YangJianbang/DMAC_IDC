<template>
  <div class="homeWarp">
    <el-container class="main_container">
      <el-header>
        <el-row :gutter="10">
          <el-col :span="24">
            <el-image :src="require('@/assets/logo_2.png')"></el-image>
          </el-col>
        </el-row>
      </el-header>
      <el-main>Main
      </el-main>
      <el-footer>Footer
      </el-footer>
    </el-container>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Test"
}
</script>

<style scoped>
.main_container .el-header .el-image {
  height: 60px;
  right: 750px;
}

.homeWarp {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.main_container {
  height: 100%;
}

.main_container .el-header,
.main_container .el-footer {
  background-color: #b3c0d1;
  color: var(--el-text-color-primary);
  text-align: center;
  line-height: 60px;
}

.main_container .el-main {
  background-color: #e9eef3;
  color: var(--el-text-color-primary);
  text-align: center;
  line-height: 815px;
}
</style>