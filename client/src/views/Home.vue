<template>
  <div class="home">
    <ApolloExample/>
  </div>
</template>

<script>
// @ is an alias to /src
import ApolloExample from "@/components/ApolloExample.vue";

export default {
  name: "home",
  components: {
    ApolloExample
  }
};
</script>
