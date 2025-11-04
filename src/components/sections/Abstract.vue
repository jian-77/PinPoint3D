<script setup>
import abstract from '../mds/abstract.mdx';
</script>

<template>
  <div>
    <el-divider />

    
    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <h1 style="text-align:center; margin-bottom:20px;">Abstract</h1>
      </el-col>
    </el-row>

    <el-row justify="center" style="margin-bottom: 20px;">
  <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
    <el-image
      src="./pictures/intro.jpg"
      fit="cover"
      style="width: 100%; max-width: 600px; border-radius: 10px; display: block; margin: 0 auto;"
      alt="示例图片"
    />
  </el-col>
</el-row>

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12" style="text-align: justify;">
            <abstract />
        </el-col>
    </el-row>

    

  </div>
</template>

<style scoped>

</style>