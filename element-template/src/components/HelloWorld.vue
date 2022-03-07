<template>
  <div class="hello">
    <el-container>
      <el-image fit="contain" :src="require('@/assets/logo_1.png')"></el-image>
      <body>
      <h1>Welcome to Computer Science Information Data Center</h1>
      </body>
      <hr>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body {
  font-family: 微软雅黑, 宋体;
  font-size: xx-large;
  color: #409eff;

}
</style>
