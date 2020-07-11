<template>
  <child-component :myProp="preciousThing"></child-component>
</template>

<script>
import Component2 from "./Component2";

export default {
  name: "Component1",
  components: {
    "child-component": Component2
  },
  data() {
    return {
      preciousThing: "ring"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
