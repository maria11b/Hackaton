<template>
  <v-content>
    <v-container fluid fill-height>
      <Map/>
    </v-container>
  </v-content>
</template>
<script>
import Map from '@/components/Map/Google'

export default {
  components: {
    Map
  }
}

</script>
