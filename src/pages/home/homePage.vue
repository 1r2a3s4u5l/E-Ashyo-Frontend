<template>
  <div>
    <h1>home page</h1>
    <MainLayout>
      <router-view></router-view>
    </MainLayout>
  </div>
</template>

<script setup lang="ts">
import MainLayout from "../../layouts/MainLayout.vue";
</script>

<style scoped></style>
