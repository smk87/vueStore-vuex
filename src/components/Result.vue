<template>
  <p>Counter is: {{ doubleCounter }}</p>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  computed: { ...mapGetters(["doubleCounter", "stringCounter"]) }
};
</script>