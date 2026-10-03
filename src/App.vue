<script setup>
// 1. 從 components 資料夾把三個圖表元件 import 進來
import BarChart from './components/BarChart.vue';
import LineChart from './components/LineChart.vue';
import ScatterPlot from './components/ScatterPlot.vue';
import test0 from './components/test0.vue';
</script>

<template>
  <div style="padding: 20px">
    <h1>Vue 3 + Vite + D3.js 視覺化儀表板</h1>

    <!-- 2. 像 HTML 標籤一樣直接使用這三個元件 -->
    <div class="chart-container">
      <BarChart />
      <LineChart />
      <ScatterPlot />
      <test0 />
    </div>
  </div>
</template>

<style scoped>
.chart-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
</style>
