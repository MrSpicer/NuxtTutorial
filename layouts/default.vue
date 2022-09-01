<template>
  <div>
    <h1>This is a custom template header</h1>
    <div v-if="$nuxt.isOffline">You are offline</div>
    <Nuxt />
  </div>
</template>
