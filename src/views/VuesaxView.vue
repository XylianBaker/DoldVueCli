<template>
  <div class="Coffee">
    <CoffeeComponent :aboutText="'coffee ☕💖'" />
  </div>
</template>

<script lang="ts">
import CoffeeComponent from "@/components/CoffeeComponent.vue";
export default {
  components: {
    CoffeeComponent,
  },
};
</script>