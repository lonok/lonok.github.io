<template>
  <v-app>
    <v-navigation-drawer app>
    Menu lateral
    </v-navigation-drawer>

    <v-app-bar
      app
      color="black"
      dense
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="img/logo-symbol.png"
          transition="scale-transition"
          width="32"
        />

        <h1 class="title">Lonok</h1>
      </div>


      <v-spacer></v-spacer>

      <v-btn
        href="https://telegram.me/leonardofilipe"
        target="_blank"
        color="primary"
        depressed
        small
      >
        <v-icon>mdi-search</v-icon>
        <span class="mr-2">contato</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>

<style>
#app{ background-color: #e1e1e1!important; }
h1,h2,h3,h4,h5 { font-family:'Viga'; }
</style>