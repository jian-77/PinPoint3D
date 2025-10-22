<script lang="ts" setup>
import { VueCompareImage } from 'vue3-compare-image';

const inputImagePath1 = './image_inner/Agile_0355.png';
const outputImagePath1 = './image_inner/PartAgile_0355.png';

const inputImagePath2 = './image_inner/5_origin.png';
const outputImagePath2 = './image_inner/5_part_click11.png';

const inputImagePath3 = './image_inner/100_origin.png';
const outputImagePath3 = './image_inner/100_part_click4.png';

const inputImagePath4 = './image_inner/0647_origin.png';
const outputImagePath4 = './image_inner/0647_part_click4.png';

const inputImagePath5 = './image_inner/1origin.png';
const outputImagePath5 = './image_inner/1after.png';

const inputImagePath6 = './image_inner/2origin.png';
const outputImagePath6 = './image_inner/2after.png';


</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">Single Object Segmentation Examples</h1>
    </el-row>

    <el-row justify="center">
        <el-col :xs="24" :sm="12" :md="6" :lg="6" :xl="6">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath1" 
                    :right-image="outputImagePath1"
                    :hover="true"
                />
            </el-row>
        </el-col>

       <el-col :xs="24" :sm="12" :md="6" :lg="6" :xl="6">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath2" 
                    :right-image="outputImagePath2"
                    :hover="true"
                />
            </el-row>
        </el-col>

        <el-col :xs="24" :sm="12" :md="6" :lg="6" :xl="6">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath3" 
                    :right-image="outputImagePath3"
                    :hover="true"
                />
            </el-row>
        </el-col>


       <el-col :xs="24" :sm="12" :md="6" :lg="6" :xl="6">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath4" 
                    :right-image="outputImagePath4"
                    :hover="true"
                />
            </el-row>
        </el-col>
    </el-row>

    <!-- 新增一行，放第5和第6组图片 -->
     <el-row justify="center">
      <h1 class="section-title">Multi Object Segmentation Examples</h1>
    </el-row>

    <el-row justify="center">
        <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" style="padding: 0 12px;">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath5" 
                    :right-image="outputImagePath5"
                    :hover="true"
                />
            </el-row>
        </el-col>
       <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" style="padding: 0 12px;">
            <el-row style="margin-top: 20px;" >
                <VueCompareImage 
                    :left-image="inputImagePath6" 
                    :right-image="outputImagePath6"
                    :hover="true"
                />
            </el-row>
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>

</style>
