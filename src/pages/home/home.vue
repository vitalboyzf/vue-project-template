<template>
  <div class="home">
    <h1>{{ msg }} Page</h1>
  </div>
</template>

<script>
export default {
  name: "Home",
  created() {},
  mounted() {},
  props: {
    msg: {
      type: String,
      default: "Home",
    },
  },
  data: function () {
    return {};
  },
  computed: {},
  methods: {},
  components: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
