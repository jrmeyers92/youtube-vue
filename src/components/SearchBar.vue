<template>
  <div>
    <input @input="onInput" />
  </div>
</template>

<script>
export default {
  name: "SearchBar",
  methods: {
    onInput: (e) => {
      console.log(e.target.value);
    },
  },
};
</script>

<style></style>
