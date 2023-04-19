<template>
<div id="border">
  <div id="app">
    <img alt="pic" src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBK1FYQkE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--7e1664e86538c0229c78dd396a553be11a3a23a3/24955525_1996255580657615_7347369665562323013_o.jpg" style="width:250px;height:250px;">
    <Profile msg="Personal Information"/>
    <Education msg="Education"/>
    <Skills msg="Skills">

  </div>
</template>

<script>
import Profile from './components/Profile.vue';
import Education from './components/Education.vue';
import Skills from './components/Skills.vue';

export default {
  name: 'App',
  components: {
    Profile, Education, Skills
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
	display: flex;
	justify-content: center;
	align-items: center;
}

#border {
  border: 2px solid black;
  padding: 100px;
  border-radius: 0px;
}

</style>
