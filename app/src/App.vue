<script setup lang="ts"></script>

<template>
  <div class="container mx-auto py-20">
    <h1>You did it!</h1>
    <fwb-alert type="success">
      Success! You can now use Flowbite Vue in your Vue application 🎉
    </fwb-alert>
    <p class="text-2xl">
      Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
      documentation
    </p>
  </div>
</template>

<script setup lang="ts">
  import { FwbAlert } from 'flowbite-vue'
</script>
