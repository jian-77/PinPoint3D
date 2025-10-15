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

</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">Image Inner Comparison</h1>
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

  </div>
</template>

<style scoped>

</style>
