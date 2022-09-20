<template>
  <v-app>
    <v-navigation-drawer permanent>
      <router-view>
        <nav>
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link> |
          <router-link to="/login">Login</router-link>
        </nav>
      </router-view>
    </v-navigation-drawer>
    <p>Navigation Drawer</p>


    <!-- Sizes your content based upon application components -->
    <v-main>

      <!-- Provides the application the proper gutter -->
      <v-container fluid>

        <!-- If using vue-router -->

      </v-container>
    </v-main>

  </v-app>
</template>

<script>

export default {
  name: 'App',

  data() {
    return {
      items: [
        { title: 'Dashboard', icon: 'mdi-view-dashboard' },
        { title: 'Photos', icon: 'mdi-image' },
        { title: 'About', icon: 'mdi-help-box' },
      ],
      right: null,
    }
  },
}
</script>
