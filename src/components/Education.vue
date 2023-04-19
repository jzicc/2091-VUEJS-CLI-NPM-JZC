<template>
  <div class="education">
    <h1>{{ message }}</h1>
    <p>
      {{ msg }}
   </p>
   <p2>{{ msg2 }}</p2>
   
    <hr class="style1">

    
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Education',
  data() {
    return {
      message: 'Education',
      msg: 'Elementary/JHS/SHS: Holy Family Academy',
      msg2: 'College: Holy Angel University'

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
