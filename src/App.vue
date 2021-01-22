<template>
  <h1 class="text-blue-500">Hello World</h1>
  <span @click="toggleDarkMode">
    toggle
  </span>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  methods: {
    toggleDarkMode () {
      document.documentElement.classList.toggle('dark')
    }
  }
})
</script>

<style>
</style>
