<template>
  <ul class="navList">
    <li v-for="(link, index) in links" :key="index" class="navListItem">
      <NuxtLink :to="link.path">
        <span class="navLinkTitle">{{ link.name }}</span>
      </NuxtLink>
    </li>
  </ul>
</template>

<script setup>
defineProps({
  links: {
    type: Array,
    required: true,
    default: () => [],
  },
});
</script>

<style lang="scss" scoped></style>
