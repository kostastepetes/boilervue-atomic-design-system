<template>
 
  <div>
    <h1>{{ msg1 }}</h1>
    <h2> {{ msg2 }}</h2>
    <h3> {{ msg3 }}</h3>
    <h3> {{ msg4 }}</h3>
    <img src="../../assets/atomic-design-process.png" width="1000px" height="450px">
  </div>
  
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      msg1: 'Welcome to BoilerVue Design System',
      msg2: '🟢 BoilerVue is an Atomic Design System for Vue.js',
      msg3: 'What is Atomic Design?',
      msg4: 'Atomic design is atoms, molecules, organisms, templates, and pages concurrently working together to create effective interface design systems. Atomic design is not a linear process, but rather a mental model to help us think of our user interfaces as both a cohesive whole and a collection of parts at the same time.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  text-align: center;
  margin-bottom: 20px;
}
h2 {
  text-align: center;
  margin-top: 50px;
}
h3 {
  text-align: center;
}
</style>
