<template>
  <div class="hello">
    <appHeader></appHeader>
    <div class="a">bb</div>
  </div>
</template>

<script>
import AppHeader  from './test'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
    components:{
      AppHeader 
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.a{color: springgreen}
</style>
