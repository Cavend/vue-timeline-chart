// https://developers.google.com/chart/interactive/docs/gallery/timeline

<template>
  <div id="app">
    <el-container>
      <el-main>
        <TimelineChart />
      </el-main>
    </el-container>
  </div>
</template>

<script>
import TimelineChart from '@/components/timeline-chart.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    TimelineChart
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
