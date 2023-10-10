<script setup>
import SideBar from './components/Sidebar.vue'
import MainContent from './components/MainContent.vue'
</script>

<template>
  <SideBar />
  <div class="right">
    <MainContent />
  </div>
</template>

<style scoped>
.right {
  flex: 0 0 90%;
  background-color: #fff;
}
</style>
