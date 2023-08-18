<template>
  <div class="layout">
    <v-layout>
        <v-navigation-drawer v-model="drawer" location="right">
            <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quidem, facilis blanditiis iure recusandae voluptatibus optio consequatur vero aliquam ea, porro fuga non ipsam quos hic, sit ipsum ad cumque harum.
            </p>

        </v-navigation-drawer>
      <v-app-bar></v-app-bar>
      <v-footer :app="true">
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi error ab perferendis excepturi? Repellat, officiis sapiente ex facilis a necessitatibus fugit quasi cupiditate! Distinctio quasi porro non ea, neque facere.
        </p>

      </v-footer>
    </v-layout>
  </div>
</template>
<script>
    export default{
        data: () => ({
            drawer: true,

        }),
    };

</script>
