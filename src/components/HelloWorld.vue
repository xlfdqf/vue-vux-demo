<template>
  <div class="hello">
    <x-header></x-header>
  </div>
</template>

<script>
import { XHeader } from "vux";
export default {
  name: "HelloWorld",
  components: {
    XHeader
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
