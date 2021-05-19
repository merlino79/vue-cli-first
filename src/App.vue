<template>

  <div id="app">
   
    <Title/>
    <Main/>
  </div>

</template>

<script>

import Title from '@/components/Title.vue'
import Main from '@/components/Main.vue'

export default {

  name: 'App',
  components: {
    Title,
    Main,
  }

}
</script>

<style>

</style>