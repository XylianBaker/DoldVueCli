<template>
  <div class="buttons">
    <img src="../assets/coffee.png" alt="coffee" />
    <h1>This is not an about page, it is about {{ aboutText }}</h1>
    <ButtonGroup />
  </div>
</template>

<script lang="ts">
import ButtonGroup from "@/components/ButtonGroup.vue";
import { PropType } from "vue";
export default {
  components: {
    ButtonGroup,
  },
  props: {
    aboutText: {
      type: String as PropType<string>,
      default: "coffee",
    },
  },
};
</script>