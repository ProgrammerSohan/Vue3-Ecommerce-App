<!-- eslint-disable prettier/prettier -->
<!-- eslint-disable prettier/prettier -->
<template>
  <div class="layout">
    <v-layout>
      <CartDrawer />
      <v-main>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, nesciunt!
          Facere placeat sit commodi tempora qui. Aspernatur quis, repellendus commodi
          cumque a dolores beatae quae sed explicabo nulla iusto ut.
        </p>
      </v-main>
      <AppNav />
      <AppFooter />
    </v-layout>
  </div>
</template>
<script>
import AppNav from "./AppNav.vue";
import AppFooter from "./AppFooter.vue";
import CartDrawer from "./CartDrawer.vue";
export default {
  data: () => ({
    drawer: true,
  }),
  components: {
    AppNav,
    AppFooter,
    CartDrawer,
  },
};
</script>
