<template>
  <div>
    <NuxtLink to="/somepage">Some page</NuxtLink>
    <Tutorial />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
