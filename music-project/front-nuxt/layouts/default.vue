<template>
  <div>
    <Header />
    <slot />
  </div>
</template>

<script setup lang="ts">
import Header from "~/components/Header.vue"

await useAuthUser()
</script>