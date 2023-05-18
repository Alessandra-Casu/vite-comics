<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
import AppBlackRow from "./components/AppBlackRow.vue";
import AppMenu from "./components/AppMenu.vue";

export default {
  components: {
    AppHeader,
    AppMain,
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
    <AppMain> </AppMain>
  </main>

  <AppFooter></AppFooter>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
