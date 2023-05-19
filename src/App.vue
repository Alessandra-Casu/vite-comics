<script>
import AppHeader from "./components/AppHeader.vue";
import AppUpFooter from "./components/AppUpFooter.vue";
import AppFooter from "./components/AppFooter.vue";
import AppBlackRow from "./components/AppBlackRow.vue";
import AppMenu from "./components/AppMenu.vue";

export default {
  components: {
    AppHeader,
    AppUpFooter,
    AppFooter,
    AppBlackRow,
    AppMenu,
  },
};
</script>

<template>
  <AppHeader></AppHeader>
  <main>
    <AppBlackRow></AppBlackRow>
    <AppMenu></AppMenu>
  </main>

  <footer>
    <AppUpFooter> </AppUpFooter>
    <AppFooter></AppFooter>
  </footer>
</template>

<style lang="scss">
@use "./assets/styles/general" as *;
</style>
