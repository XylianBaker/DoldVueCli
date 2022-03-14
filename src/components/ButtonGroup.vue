
<template>
  <div class="center">
    <vs-button :active="active == 0" @click="active = 0">
      Espresso💖
    </vs-button>
    <vs-button :active="active == 1" @click="active = 1"> Latte💀 </vs-button>
    <vs-button disabled>Disabled</vs-button>
  </div>
</template>
<script lang="ts">
export default {
  data() {
    return {
      active: 0,
    };
  },
};
</script>

<style>
.center {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
</style>