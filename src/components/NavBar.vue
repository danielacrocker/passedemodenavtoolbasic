<template>
  <div>
    <nav>
      <v-toolbar>
        <v-toolbar-title class="grey--text">
          <span class="font-weight-light">Site</span>
          <span>Title</span>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn text>
          <span>Sign Out</span>
          <v-icon right>exit_to_app</v-icon>
        </v-btn>
      </v-toolbar>

      <v-navigation-drawer v-model="drawer" app class="primary">
        <p>test</p>
      </v-navigation-drawer>

    </nav>
  </div>
</template>


<script>
export default {
  data: () => ({
    drawer: true
  }), 
}
</script>