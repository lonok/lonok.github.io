<template>
  <v-container class="pa-2">
    <v-row wrap align-content-md>
      <v-col class="text-center">
        <!--img src="img/logo-symbol.png" style="max-width:100px;">
        <h1>Lonok</h1-->

        <about-me></about-me>

      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  import AboutMe from './About'

  export default {
    name: 'Home',

    components: {
      AboutMe,
    },
  }
</script>
