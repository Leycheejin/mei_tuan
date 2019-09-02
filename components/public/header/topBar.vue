<template>
  <div>
    <el-row :gutter="20" class="m-header">
      <el-col :span="7">
        <geo></geo>
      </el-col>
      <el-col :span="5">
        <user></user>
      </el-col>
      <el-col :span="12">
        <navbar></navbar>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import geo from './geo'
import user from './user'
import navbar from './nav'

export default {
  name: 'TopBar',
  components: {
    geo,
    user,
    navbar
  },
  data() {
    return {}
  }
}
</script>

<style lang="scss">
@import '@/assets/css/public/layout.scss';
@import '@/assets/css/public/header/topbar.scss';
</style>
