<script>
import AppHeader from "@/components/AppHeader.vue";
import AppFooter from "@/components/AppFooter.vue";
import ProductList from "@/components/ProductList.vue";
export default {
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>
<template>
  <div id="app">
    <AppHeader />
    <!-- <router-view /> -->
    <ProductList />
    <AppFooter />
  </div>
</template>
<style>
.page {
  max-width: 400px;
  margin: auto;
  
}
</style>