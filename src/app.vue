<template>
  <div style="background: blue; font-weight: bold">
    <span>hello!</span>
    <span>{{ data.name }}</span>
  </div>
</template>
<script>
export default {
  name: "Msg",
  data() {
    return {};
  },
  props: {
    data: {
      type: Object,
    },
  },
  methods: {},
  created() {
    let that = this;
  },
};
</script>
