<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <el-button type="success" @click="handleClick">
          {{ name }}
        </el-button>
      </nav>
    </div>
  </header>
  <AppProvider />
  <!--  <RouterView />-->
</template>

<script setup lang="ts">
const name = ref('asd');

function handleClick() {
  console.log('asdhioh');
}
</script>
<style scoped></style>
