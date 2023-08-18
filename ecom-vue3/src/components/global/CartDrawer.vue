<!-- eslint-disable prettier/prettier -->
<template>
  <div class="drawer">
    <v-navigation-drawer location="right" v-model="drawer">
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quidem, facilis
        blanditiis iure recusandae voluptatibus optio consequatur vero aliquam ea, porro
        fuga non ipsam quos hic, sit ipsum ad cumque harum.
      </p>
    </v-navigation-drawer>
  </div>
</template>
<script>
export default {
  inject: ["Emitter"],
  data: () => ({
    drawer: false,
  }),
  mounted() {
    this.Emitter.on("openCart", () => {
      this.drawer = true;
    });
  },
};
</script>
