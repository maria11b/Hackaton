<template>
  <v-list dense>
    <router-link :to="item.link" :key="item.link" v-for="item in menu">
    <v-list-tile  >
      <v-list-tile-action>
        <v-icon>{{item.icon}}</v-icon>
      </v-list-tile-action>
      <v-list-tile-content>
        <v-list-tile-title>{{item.label}}</v-list-tile-title>
      </v-list-tile-content>
    </v-list-tile>
      </router-link>

  </v-list>
</template>
<script>
export default {
  data: function () {
    return {
      menu: [
        { label: 'Home', link: '/', icon: 'home' }
      ]
    }
  }
}
</script>
