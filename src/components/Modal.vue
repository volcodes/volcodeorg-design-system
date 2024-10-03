<script setup lang="ts">
import { ref } from 'vue'

defineProps<{
  title: string,
  description: string,
}>()
</script>

<template>
  <div class="fixed inset-0 bg-black bg-opacity-70 flex justify-center items-center z-50" id="modal">
    <div class="bg-gray-200 shadow-lg w-full container max-w-[768px] text-center">
      <p>This is a modal window.</p>
      <button class="mt-4 px-4 py-2 bg-gray-800 text-white rounded-md" id="close-btn">Close</button>
    </div>
  </div>
  <button class="button submit">
    <strong>{{ title }}</strong>
    <p>{{ description }}</p>
  </button>

  <!-- <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div> -->

  <!-- <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Learn more about IDE Support for Vue in the
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      >Vue Docs Scaling up Guide</a
    >.
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p> -->
</template>

<style scoped>
</style>
