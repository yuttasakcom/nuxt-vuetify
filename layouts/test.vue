<template>
  <v-app>
      <Toolbar />
      <v-content>
          <v-container>
              <nuxt />
          </v-container>
      </v-content>
  </v-app>
</template>

<script>
import Toolbar from '@/components/Header/Toolbar'
export default {
  components: {
    Toolbar
  }
}
</script>
