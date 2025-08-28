<template>  
  <div>
    <h1>This is about page</h1>
  </div>
  <div>
    <button @click="enableCustomLayout">更新布局</button>
  </div>
</template>

<script setup lang="ts">

definePageMeta({
  layout: 'another'
})

function enableCustomLayout () {
  setPageLayout('default')
}
</script>