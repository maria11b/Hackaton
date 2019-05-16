<template>
  <div>
  <v-navigation-drawer
    v-model="drawer"
    fixed
    app
  >
   <Menu/>
  </v-navigation-drawer>
  <v-toolbar color="indigo" dark fixed app>
    <v-toolbar-side-icon @click.stop="drawer = !drawer"></v-toolbar-side-icon>
    <v-toolbar-title>Application</v-toolbar-title>
  </v-toolbar>
</div>
</template>

<script>
import Menu from './Menu'
export default {
  components: {
    Menu
  },
  data: () => ({
    drawer: null
  })
}
</script>
