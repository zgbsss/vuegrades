<script>
import MenuLateral from "@/components/MenuLateral.vue";
import HeaDer from "@components/HeaDer.vue";
export default {
  components: { MenuLateral HeaDer },
};
</script>

<template>
  <MenuLateral />
  <header class="header">Cabeçalho</header>
  <main class="content">Principal</main>
  <footer class="footer">Rodapé</footer>
</template>

<style></style>
