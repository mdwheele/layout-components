<script setup>
import Card from './components/Card.vue'
import Stack from './components/Stack.vue'
import Column from './components/Column.vue'
import Columns from './components/Columns.vue'
</script>

<template>
  <div class="h-screen flex flex-col font-mono">

    <Stack gap="sm">
      <Card class="bg-blue-400 h-32">Header</Card>

      <Columns gap="sm">
        <Column class="bg-red-400" width="sm">Navigation</Column>
        <Column class="bg-green-400">Main</Column>
        <Column class="bg-orange-400" width="sm">Aside</Column>
      </Columns>

      <Card class="bg-indigo-400">Footer</Card>
    </Stack>

  </div>
</template>
