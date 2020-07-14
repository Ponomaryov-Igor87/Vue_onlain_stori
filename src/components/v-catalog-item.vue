<template>
  <div class="v-catalog-item">
    <p>item 1</p>
    <p>prais: 100</p>
    <button>add to cart</button>
  </div>
</template>

<script>
export default {
  name: "v-catalog-item",
  components: {},
  props: {},
  data() {
    return {};
  },
  computed: {},
  methods: {},
  watch: {},
  mounted() {}
};
</script>
    
<style lang="scss">
.v-catalog-item {
  flex-basis: 25%;
  box-shadow: 0 0 8px 0 #e0e0e0;
  padding: $padding * 2;
  margin-bottom: $margin * 2;
}
</style>