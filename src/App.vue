<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>אנחנו איתך</span>
        <span class="font-weight-light"> גם מרחוק</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Sales from './components/Sales'

export default {
  name: 'App',
  components: {
    Sales
  },
  data () {
    return {
      //
    }
  }
}
</script>
