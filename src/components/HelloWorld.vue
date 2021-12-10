<template>
  <div class="hello">
    <h1>{{ props.msg }}</h1>
  </div>
</template>

<script setup lang="ts">
import { ref, Ref } from "vue";
const name: Ref<string> = ref("HelloWorld");
const props = defineProps<{ msg: string }>();
</script>
<style scoped>
h3 {
  margin: 40px 0 0;
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
