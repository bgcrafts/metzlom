<template>
  <div class="app-container">
    <app-header />
  </div>
</template>

<script>
import AppHeader from "~/components/Header.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<style>
.app-container {
  background: blue;
}
</style>
