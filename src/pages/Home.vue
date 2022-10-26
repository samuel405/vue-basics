<template>
  <h1>{{ this.pageTitle }}</h1>
</template>

<script>
export default {
  name: "Home",
  props: {
    page: String,
  },
  data() {
    return {
      pageTitle: this.page,
    };
  },
};
</script>
