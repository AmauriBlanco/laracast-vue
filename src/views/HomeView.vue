<script setup>
import { useFlash } from '@/composables/useFlash'

let { flash } = useFlash()
</script>

<template>
  <main>
    <p>
      <button @click="flash('Teste', 'Id Works')">Click Me</button>
    </p>
  </main>
</template>
