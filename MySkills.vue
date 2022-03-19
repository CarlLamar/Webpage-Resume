<template>
      <div id="todo-card">
         <div class="container">
           
    
<div class="alert alert-secondary" role="alert">
    <h1>{{ msg4 }}</h1>
</div>
<br/>
    
    <br/>
    <p><b>Seminars</b></p>
    <p> Result-Oriented Web Developer</p>
    <p>Web Application & Software Architecture 101</p>
    <br/>
    <p><b>Programming Languages</b></p>
    <p>Python</p>
    <p>Java</p>
    <p>HTML</p>
    <p>CSS</p>
    <p>Javascript</p>
    <br/>
  


</div>
  </div>
  
</template>

<script>
 
  export default {
    name: 'my-skills',
    data () {
      return {
        msg4: 'Background Skills'
        
      }
    }
  }
</script>