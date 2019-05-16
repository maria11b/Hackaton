<template>
  <v-app id="inspire">
    <Header/>
    <Content/>
    <Footer/>

  </v-app>
</template>

<script>
import Header from '@/components/Layout/Header'
import Footer from '@/components/Layout/Footer'
import Content from '@/components/Layout/Content'

export default {
  components: {
    Header,
    Footer,
    Content
  },
  props: {
    source: String
  }
}
</script>
