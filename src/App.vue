<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Brent</span>
        <span class="font-weight-light">Seaton</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-1">Home</span>
      </v-btn>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-1">About Me</span>
      </v-btn>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-1">Recent Work</span>
      </v-btn>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-1">Contact Me</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <Top/>
    </v-content>
  </v-app>
</template>

<script>
import Top from './components/Top'

export default {
  name: 'App',
  components: {
    Top
  },
  data () {
    return {
      //
    }
  }
}
</script>
