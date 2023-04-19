<template>
  <div class="skills">
    <h1>{{ message }}</h1>
    <p>
      Web Design with HTML & CSS 
   </p>
   
    
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data () {
    return {
      message: 'Skills',
      msg2: 'Web Design with HTML & CSS'
    }
  }
}
</script>




<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
