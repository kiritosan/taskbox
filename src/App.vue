<template>
  <div id="app">
    <!-- <task-list /> -->
    <InboxScreen />
  </div>
</template>

<script>
import InboxScreen from "./components/InboxScreen.vue";

export default {
  name: "App",
  components: {
    InboxScreen
  }
};
</script>

<style>
@import "./index.css";
</style>
