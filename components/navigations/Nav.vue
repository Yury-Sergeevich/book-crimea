<template>
  <NavList :links="navlink" />
</template>

<script setup>
const navlink = [
  { name: "Рубрики", path: "/categories/categories" },
  { name: "Срочно", path: "/categories/cat" },
  { name: "Отзывы", value: "comment" },
  { name: "Реклама", value: "reclama" },
  { name: "Архив", value: "zip" },
  { name: "La patrimoine", value: "La patrimoine" },
  { name: "АЛЬМАНАХ ЭТЕРНАЛИЗМА Flipbook", value: "Flipbook" },
];
</script>

<style lang="scss" scoped></style>
