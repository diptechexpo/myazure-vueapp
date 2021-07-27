<template>
  <div>{{ message }}</div>
</template>

<script>
export default {
  name: "Message",
  data() {
    return {
      message: ""
    };
  },
  async mounted() {
    const { text } = await (await fetch("/api/message")).json();
    this.message = text;
  }
};
</script>