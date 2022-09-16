<template>
  <div id="app">
    <HeaderFirst/>
    <MainSez/>
    <MainSez2/>
    <MainSez3/>
    <MainSez4/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
  </div>
</template>
<script>

import HeaderFirst from './components/HeaderFirst.vue'
import MainSez from './components/MainSez.vue'
import MainSez2 from './components/MainSez2.vue'
import MainSez3 from './components/MainSez3.vue'
import MainSez4 from './components/MainSez4.vue'





export default {
  name: 'App',
  components: {
    HeaderFirst,
    MainSez,
    MainSez2,
    MainSez3,
    MainSez4
    
    
}
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
