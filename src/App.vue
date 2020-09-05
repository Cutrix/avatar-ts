<template>
  <div id="app">
    <avatar></avatar>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Avatar from "./components/Avatar.vue";

@Component({
  components: {
    Avatar
  }
})
export default class App extends Vue {}
</script>

<style></style>
