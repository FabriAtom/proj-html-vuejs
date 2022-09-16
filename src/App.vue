<template>
  <div id="app">
    <HeaderFirst/>
    <MainSez/>
    <MainSez2/>
    <MainSez3/>
    <MainSez4/>
    <HomeFooter/>
    <LastFooter/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,500;1,300&display=swap" rel="stylesheet">
  </div>
</template>

<script>
import HeaderFirst from './components/HeaderFirst.vue'
import MainSez from './components/MainSez.vue'
import MainSez2 from './components/MainSez2.vue'
import MainSez3 from './components/MainSez3.vue'
import MainSez4 from './components/MainSez4.vue'
import HomeFooter from './components/HomeFooter.vue'
import LastFooter from './components/LastFooter.vue'

export default {
  name: 'App',
  components: {
    HeaderFirst,
    MainSez,
    MainSez2,
    MainSez3,
    MainSez4,
    HomeFooter,
    LastFooter  
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
