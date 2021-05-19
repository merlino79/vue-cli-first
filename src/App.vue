<template>

  <div id="app">
   
    <Title/>
    <Jambatron/>
  </div>

</template>

<script>

import Title from '@/components/Title.vue'

import Jambatron from './components/Jambatron.vue'

export default {

  name: 'App',
  components: {
    Title,
    
    Jambatron,
  }

}
</script>

<style>

</style>