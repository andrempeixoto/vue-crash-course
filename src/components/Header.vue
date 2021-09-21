<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    title: {
      type: String,
      default: "",
    },
  },
};
</script>

<style scoped lang="css">
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1.25 rem;
}
</style>
