<template>
  <div class="home">
    <v-navigation-drawer app>
      <!-- -->
    </v-navigation-drawer>

    <v-app-bar app>
      <!-- -->
    </v-app-bar>

    <!-- Sizes your content based upon application components -->
    <v-content>

      <!-- Provides the application the proper gutter -->
      <v-container fluid>
        <!-- If using vue-router
        <router-view></router-view> -->
        <HelloWorld/>
      </v-container>
    </v-content>

    <v-footer app>
      <!-- -->
    </v-footer>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
