<template>
  <div class="flex flex-col border-2 p-10 justify-center items-center">
    <Icp />
    <Calculator />
  </div>
</template>

<script>
import Icp from "./components/Icp.vue";
import Calculator from "./components/Calculator.vue";
export default {
  name: "App",
  components: {
    Icp,
    Calculator,
  },
};
</script>