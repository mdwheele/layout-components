<template>
  <div :class="[
    'flex-1 flex flex-col',
    { 'gap-4': gap === 'sm', 'gap-8': gap === 'lg' }
  ]">
    <slot />
  </div>
</template>

<script setup>
defineProps({
  gap: String
})
</script>