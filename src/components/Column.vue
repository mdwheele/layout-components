<template>
  <div :class="[
    'flex flex-col h-full',
    { 'flex-1': !width, 'w-32': width === 'sm'}
  ]">
    <slot />
  </div>
</template>

<script setup>
defineProps({
  width: String
})
</script>