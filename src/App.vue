<template>
  <BaseCard>
    <h1>This is a title</h1>
    <p>This is some content inside the card.</p>
  </BaseCard>
</template>

<script>
import BaseCard from "./components/BaseCard.vue";

export default {
  name: "App",
  components: {
    BaseCard,
  },
};
</script>

<style>
body {
  margin: 0;

}
#app {
  min-height: 100vh;
  width: 100vw;
  padding: 100px;
  box-sizing: border-box;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011f35 100%);
}
</style>
