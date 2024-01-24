<template>
  <div>
    <Header/>
    <Tabs />
  </div>
</template>

<script>
import Header from '../components/header.vue'
import Tabs from '../components/tabs.vue'

export default {
  name: 'IndexPage',
  components: {
    Header,
    Tabs,
  }
}
</script>

<style src="../assets/css/index.css">

</style>
