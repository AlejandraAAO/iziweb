<template>
  <v-app color="#E64442">
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
    >
      <IziLogo />
      <v-spacer />
     <v-btn
      class="ma-2"
      outlined
      color="#E64442"
    >
      Mi Cuenta
    </v-btn>

    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

<!--
    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  
-->
  </v-app>
</template>

<script>
import IziLogo from '~/components/IziLogo.vue'

export default {
  components: {
    IziLogo
  }
}

</script>
