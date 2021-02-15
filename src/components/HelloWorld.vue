<template>
  <div class="hello">
    <h1 v-if="msg">{{ msg }}</h1>
    <h1 v-else>Untitled</h1>
    
    <div>
      Hello World
    </div>
  </div>
</template>


<script>

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #111;
  letter-spacing: .12em;
  text-transform: uppercase;
}
</style>
