<template>
</body>
  <div class="profile">
    <h2>{{ message }}</h2>
    <p>
      {{ msg }}
   </p>
   
   <p>
     {{ msg2 }}
   </p>
   <p>
     {{ msg3 }}
   </p>
  <p>
      {{ msg4 }}
   </p>
   <p>
     {{ msg5 }}
   </p>
    <hr class="style1">

    
    </ul>
  </div>
  </body>
</template>

<script>
export default {
  name: 'Profile',
  data () {
    return {
      message: 'Personal Information',
      msg:'Name: Carreon, John Zacqueo I.',
      msg2: 'Age: 21',
      msg3: 'Objective: As a web developer, my objective is to create user-friendly and efficient websites that are visually appealing and easy to navigate. I utilize my skills in HTML, CSS, JavaScript, and PHP to develop websites that meet all the requirements of the client.',
      msg4: 'School Email: jicarreon@student.hau.edu.ph',
      msg5: ' Contact Number: 09123456789'
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
