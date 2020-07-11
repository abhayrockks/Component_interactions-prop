<template>
  <h2>The precious thing: {{myProp}}</h2>
</template>

<script>
export default {
  name: "Component2",
  props: ['myProp']
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
