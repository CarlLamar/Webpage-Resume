<template>
      <div id="todo-card">
         <div class="container">
    
<div class="alert alert-info" role="alert">
    <h1>{{ msg2 }}</h1>
</div>
    <br/>
    <p><b>Objective</b></p>
    <p>Seeking an entry-level position to begin my career in a high-level professional environment. To secure employment with a reputable company, where I can utilize my skills.</p>
    <br/>
    
    <p><b>Course</b></p>
    <p>Bachelor of Science in Information Technology</p>
    <br/>
    <p><b>Specialization</b></p>
    <p>Web Development</p>
    <br/>

</div>
  </div>
  
</template>

<script>
 
  export default {
    name: 'todo-card',
    data () {
      return {
        
        msg2: 'Carl Delas-Alas Gegante'
      }
    }
  }
</script>