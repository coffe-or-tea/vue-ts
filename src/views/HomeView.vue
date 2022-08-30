<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div>{{test[0].id}}</div>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import { DeviceTyp } from './interface'
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

const test:DeviceTyp = ref([
  {
    id: 123,
    name: '1234'
  }
])
</script>
