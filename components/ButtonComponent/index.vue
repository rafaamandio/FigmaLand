<template>
  <NuxtLink
    :to="actionUrl"
    class="self-end bg-primary flex gap-2 py-[6px] pl-1 pr-2 rounded-[32px] text-sm items-center"
    target="_blank"
  >
    {{ title }}
  </NuxtLink>
</template>

<script setup>
const props = defineProps({
  actionUrl: String,
  title: String
})
</script>