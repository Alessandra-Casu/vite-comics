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

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  height: 100vh;
}
</style>
