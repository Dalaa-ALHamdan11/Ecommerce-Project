<template>

  <div>
    <Header/>
    <RouterView />
  </div>

</template>

<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header.vue';
</script>

<style>
.container {
  max-width: calc(1440px - 170px);
    width: 100%;
    margin: auto;
}

.btn {
  background: transparent;
  border: none;
  transition: .3s;
  cursor: pointer;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

img {
  width: 100%;
}

span .icon {
  display: flex;
  align-items: center;
}
</style>
