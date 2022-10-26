<template>
  <table>
    PaginatedTable
  </table>
</template>

<script>
export default {
  name: "PaginatedTable",
  data() {
    return {
      page: 1,
      itemsPerPage: [10, 20, 30, 40, 50],
    };
  },
};
</script>