<script setup>
import { useFlash } from '@/composables/useFlash'

let { flash } = useFlash()
</script>
<template>
  <div>
    <p>
      <button @click="flash('Yay!', 'Id Works on The About page', 'info')">Click Me</button>
    </p>
  </div>
</template>
