<template>
  <p>{{asd}}</p>
</template>
<script>
import { useRouter } from "vue-router";
export default {
  name: "HelloWorld",
  data() {
    return {
      asd: "assdsdad"
    };
  },
  setup() {
    const router = useRouter();
    const toHome = () => {
      router.push({
        name: "home"
      });
    };
    return {
      toHome
    };
  }
};
</script>
<style  scoped>
</style>
