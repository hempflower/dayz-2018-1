<template>
  <q-layout view="hHh lpR fFf">
    <q-page-container>
        <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>
<style scoped>
.full {
  min-height: 100vh;
}
</style>
