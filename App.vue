<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    
    <!----- Demo 1. Insert The component name, as shown below -->
    <todo-card></todo-card>
    <about-us></about-us>
    <MySkills></MySkills> 

  </div>
</template>

<script>
//import the newly created components
import TodoCard from './components/TodoCard'
import AboutUs from './components/AboutUs'
import MySkills from './components/MySkills'


export default {
  components: { TodoCard },
  name: 'app',
  components : {
    TodoCard,
    AboutUs,
    MySkills
  },
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>