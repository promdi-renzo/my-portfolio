<template>
<div class="app-container">
  <Navbar/>
  <Contents/>
</div>

</template>

<script>
import Navbar from '../src/components/Navbar.vue'
import Contents from '../src/components/Contents.vue'
export default {
  name: 'App',
  components:{
    Navbar,
    Contents
  }
}
</script>

<style>
*{
  margin: 0px;
  padding: 0px;
}

</style>
