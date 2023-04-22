<template>
  <div>
    <h1>Jobs detail page</h1>
    <p>the job id is {{ id }}</p>
  </div>
</template>

<script>
export default {
  props: ["id"],
  // data() {
  //   return {
  //     id: this.$route.params.id,
  //   };
  // },
};
</script>

<style></style>
