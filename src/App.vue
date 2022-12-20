<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoHeader from "@/components/BlocoHeader.vue";
import BlocoPrincipal from "@/components/BlocoPrincipal.vue";
import BlocoFooter from "@/components/BlocoFooter.vue";
export default {
  components: { MenuLateral, BlocoHeader, BlocoPrincipal, BlocoFooter },
};
</script>
<template>
  <MenuLateral />
  <BlocoHeader />
  <BlocoPrincipal />
  <BlocoFooter />
</template>
<style></style>
